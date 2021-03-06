# 宗教的に PHP-FIG 標準に従うこと #

FIG とは「フレームワーク相互運用性グループ」のことです。

[PHP-FIG](http://www.php-fig.org/) は、2009 年に php|tek の多数のフレームワーク開発者によって作成されました。それ以来、様々な他のメンバーが応募して採択され、グループのサイズを最初の 5 から 20 以上に増やしました。

PHP-FIG に関しては多くの論争が存在します。一部の人々は、PHP そのものに由来して PHP コミュニティに起こった最善のことと考えていますが、他は最善の何かを忘れてしまったグループとみなしています。

PHP-FIG にまつわる問題のひとつは、彼らの [FAQ](http://www.php-fig.org/faqs/) にあるこの部分のように自己紹介していることです:

> グループの背後にある発想は、プロジェクト代表者たちが、プロジェクト間の共通点について話し合って、共同で作業する方法を見つけることです。私たちの主なオーディエンスはお互いですが、残りの PHP コミュニティが見ていることはとても意識しています。他の人々が私たちがやっていることを採用したいなら、やるのは歓迎ですが、採用してもらうことが目的というわけではありません。グループの誰も、プログラマーとして、あなたのアプリケーションを構築する方法を教えたいとは思っていません。

しかし、グループのいくつかのメンバーの作業を見ると、その目的が上記の宣言とはまったく反対であることが明確に分かります。これらのメンバーは、PHP-FIG が、**このグループのもともとの名称でもある** 信頼された「PHP 標準グループ」になるよう、飽くなき努力をしています。彼らのやりかたは、自分の書籍、ウェブサイト、ブログ投稿、フォーラムなどで PHP-FIG の作業を「モダン PHP」と分類し、他の方法を逆に分類することです。

PHP-FIG にまつわる問題のひとつは、多くのフレームワークとオープンソースプロジェクトがいくつかの標準を採用しているにもかかわらず、これらの標準は主に「フレームワークの視点」からの問題に対処しているため、多くの現実の業界の状況で実に使いづらくなっています。

多くの人々が、非常に効率的で、安全で、費用対効果の高い、顧客が購入して使いたいと思うような、産業向けのソフトウェアを開発しています。彼らは、フレームワーク狂信者のニーズに合致するべきだという標準に悩まされることはありません。彼らがそうしようとすると、ビジネスの災害になるでしょう。

何らかの標準グループを作成する必要がある場合、フレームワークとオープンソースの CMS プロジェクト開発者だけでなく、PHP コミュニティ全体の利益を反映する必要があります。それは、PHP プログラミング言語そのものの開発者によって表されなければならず、投票権を持つはるかに大きなメンバーシップによって表明されなければなりません。

PHP-FIG によって開発された標準 - オートローダー標準 PSR-0 と PSR-4 およびその他標準のいくつか - を採用すると選択した場合、あなたがソフトウェアをどうコーディングするかに直接影響します。

多くの産業で求められる、スケーラビリティがあり、ランタイムクリティカルで、コスト効率の高いソフトウェアは、単純に言って、これらの PHP-FIG の標準を使用して開発することはできません。

**間違った方法**: 宗教的に PHP-FIG に従うこと。 ![だめ](/img/thumbs-down.png)
