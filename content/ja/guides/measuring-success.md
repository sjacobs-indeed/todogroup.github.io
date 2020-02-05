# オープンソース プログラムの成功度を測る

#### オープンソース プログラムのマネージャーは、活動のROIを明らかにしなければなりません。このガイドでは、組織がオープンソースのプログラム、プロジェクト、およびコントリビューションを評価する標準的な方法を概説します。

#### 何を測定し、どのように成功を定義し、その情報をどう使ってオープンソース プログラムの目標達成を促進し、有効性を立証し、サポートを得るかを学んでください。

**内容**

1. [成功をどのように定義するか](#成功をどのように定義するか)
2. [なぜ目標を設定するのか](#なぜ目標を設定するのか)
3. [どのように目標を設定するか](#どのように目標を設定するか)
4. [共通の目標](#共通の目標)
5. [何をトラッキングするのか](#何をトラッキングするのか)
6. [トラッキングすべきその他のメトリクス](#トラッキングすべきその他のメトリクス)
7. [結論](#結論)

[ガイド一覧 »](https://www.linuxfoundation.jp/resources/open-source-guides/)
[GitHub上で貢献する »](https://github.com/todogroup/guides)

#### このガイドの貢献者

**Chris Aniszczyk**
COO of CNCF

**Christine Abernathy**
Open Source Developer Advocate at Facebook

**Joe Beda**
Co-founder and CTO at Heptio

**Gil Yehuda**
Senior Director of Open Source
at Oath (Yahoo + AOL)

**Sarah Novotny**
Kubernetes Community Manager at Google

セクション 1

## 成功をどのように定義するか

賢明な組織は、オープンソース開発への投資の価値を理解し、オープンソースの活用、参加に関連する目標を設定します。しかし、各々のオープンソース プログラムは、成功に対して少しずつ異なった定義をしています。設定した目標やトラッキングするメトリクスは、開発者を募集するためであったり、オープン イノベーションを通じて新しいアイデアや技術を導入することであったり、市場投入までの時間を短縮したり、開発コストを削減するなど、企業がオープンソースに投資する理由により異なったものになるでしょう。

あなた自身の戦略に従って目標を設定することが重要です。また、オープンソース戦略があなたの会社のビジネス戦略と一致したものとなるよう、経営幹部チームの支持を得てください。とはいえ、業界、製品、ビジネス戦略にかかわらず、オープンソースのプログラム マネージャーが成功を測る標準的な方法がいくつかあります。以下がその方法です。

- 外部のオープンソース プロジェクトにおけるあなたの会社の開発者の参加状況、および、彼らの影響力
- オープンソース コミュニティにおけるあなたの組織の評判
- 才能のある開発者を雇用し、維持する能力
- あなたの組織のオープンソース プロジェクトの健全性、および組織の開発者が貢献しているビジネス上重要なプロジェクトの健全性
- オープンソース ライセンス コンプライアンスをどのようにして正しく管理しているか

セクション 2

## なぜ目標を設定するのか

オープンソース プログラムが、何を、どのようにトラッキングするかを議論する前に、目標を設定し、目標に対する達成度を測定することによって、何が得られるかについて、少し話しましょう。

まず重要なことは、あなたの目標に対する進捗状況をトラッキングすることにより、投資しているオープンソース プロジェクト（外部か内部かにかかわらず）が健全な状態にあるかどうか、すなわち、彼らはコミュニティに応え、会社をよく代表し、オープンソース プログラムのより広い目標を達成するのを後押ししているかを確認できるようになるということです。定期的なトラッキングは、オープンソース プロジェクトのベンチマーク（基準）設定に役立ち、また、プロジェクトが軌道から外れたり、法的コンプライアンスが守られていなかったり、あるいは、プロジェクトを単に終息させる必要がある状況で、正しい方向へと修正させることを可能とする早期警戒システムとして機能します。

注意深く（そして戦略的に）実施された測定評価は、上層部への報告において大切なインプットになります。定期的に報告を行うことにより、プログラムがその目標と全体的なビジネス戦略にそって推進されること確かにし、プログラム マネージャーが経営幹部から、プログラムに対するサポートを得るのを助けます（特にあなたが目標を達成していたり、あるいは目標を超えていたりする場合は）。

たとえば、Facebook社のオープンソース プログラム オフィスでは、オープンソース プロジェクトの前月比の成果を定期的に内部で公開し、経営幹部に対しても報告書を送付しています。

> **「報告書は認識を高める良い方法です。Facebook社ではオープンソースを組織として高く評価していますが、それでも常に社内で自分自身をアピールし、あなたの価値を示すのは良いことです。」**
> 
> [**Christine Abernathy**](https://twitter.com/abernathyca)  **– Open Source Developer Advocate at Facebook**

成果を定期的に公表することで、将来的にパートナー、ユーザー、および開発者となる可能性のある人々に向けて、あなたの組織のオープンソース活動に対する認識を高めるのに役立ちます。

良かったもの、悪かったもの、たとえ酷いものでも、結果について言葉に出して表明することで、オープンソース コミュニティで、あなたのプログラムの透明性が増し、説明責任に対する姿勢が理解され、信頼性が向上します。[Facebook](https://code.fb.com/android/facebook-open-source-2016-year-in-review/)社や[Google](https://opensource.googleblog.com/2016/10/google-open-source-report-card.html)社のオープンソース成績表の例を参照してください。

セクション 3

## どのように目標を設定するか

あなたがオープンソース プログラムに対する高い目標を設定するのは良いことですが、そこにどのように到達するのか、どのようなタイムラインで到達するのかについてのリーゾナブルな道筋を設定してください。まず、パフォーマンスのベースラインを確立するために、測定を開始しましょう。データを収集するための適切なツールをセットアップし、正しいデータソースから、あなた（そしてあなたのマネージャー）が理解できるフォーマットで出力されることを確認してください。多くの組織では、オープンソース プログラムのメトリクスを目的としたダッシュボードを作成し、すべてのデータを一か所でトラッキングでき、進行状況を一目で把握できるプロジェクト スナップショットを提供しています（本ガイド集の「[オープンソース プログラムを管理するためのツール](https://www.linuxfoundation.jp/resources/open-source-guides/tools-managing-open-source-programs/)」を参照）。

 ![](https://www.linuxfoundation.jp/wp-content/uploads/2017/09/CNCF-dashboard-768x447.png "Cloud Native Computing Foundationのプロジェクト ダッシュボード")
Cloud Native Computing Foundationのプロジェクト ダッシュボード

つぎに、すべてのオープンソース プログラム マネージャーとその関係者（Facebook社ではエンジニアリングのリーダーとプロジェクト メンテナーも含まれます）を集めて、グループとして、次の3〜6か月間における、小規模で、達成可能な目標を決めます。その期間の終わりに、あなたがどのように目標を達成したかを振り返り、それに基づいて、次のステップに対する目標と戦術を調整します。

> **「私はコミュニティが何を『苦痛』として感じているかをベースにメトリクス（指標）を見つけ出す傾向があります。そのようなメトリクスが、コミュニティの『苦痛』を減らし、『健康』になる方向に変わるように努力します。」**
> 
> [**Sarah Novotny**](https://twitter.com/sarahnovotny) **– Kubernetes Community Manager at Google**

ベースライン パフォーマンスのメトリクスに加えて、オープンソース プログラムの目標を設定する際に考慮すべき点がいくつかあり、以下に示します。

- **戦略との合致：** あなたの目標は、あなたの会社のコアビジネス戦略、製品目標、およびその他の内部ビジネス目標と合致していますか？
- **コントロールできる範囲：** プログラム マネージャーは、結果に対して直接的にコントロールできる立場ですか？それとも、エンジニアリング、法律、その他の組織と共同で行っていますか。あなたのコントロールできる範囲内で達成可能な目標を設定してください。
- **プロジェクトのバリエーション：** 目標は、プロジェクトの目的、コミュニティの構成、技術のスタック、およびその他の変数に応じて、プロジェクトごとに異なっているはずです。たとえば、Facebook社は、同社のJavascriptプロジェクトは頻繁にフォークされる傾向にあることに気づきました。多くのトラッキング サイクルの後に、これらのメトリクスは必ずしもこのタイプのプロジェクトの健全性を測定するための最良の指標ではないと、ようやく学びました。
- **質と量：** すべての目標を数値化するべきではありません。プロジェクトの品質向上のためのプロセス改善は、より重要とまでは言えなくとも、同じくらいに重要です。あなたがすべての数値目標を達成しているからといって、必ずしもあなたのプロジェクトが健全であるとは限りません。逆に、成長が止まっているように見える小さなプロジェクトが非常に健全であることもあります。Novotnyは言います。「6名程度のコア コントリビューターと活発ではあるがメンテナーではないその倍程度のメンバーで、健全な議論があり、プルリクエストを素早く処理し、厄介な機能追加のディスカッションも明確な始まりと終わりをもって処理されるプロジェクトがあるかもしれません。それは信じられないほど健全なコミュニティかもしれませんが、ニッチなプロジェクトなので、GitHubの人気度を表すスターやフォークを多くは持っていないでしょう。したがって私は、コミュニティはどのように交流しているのか、新しいリーダーシップがどのように成長し、育てられているのか、悩みはどのように解決・改善されているのかを見る傾向があります。」

セクション 4

## 共通の目標

オープンソース プログラムの成功を評価するべき状況になると、コントリビューターの総数、コードの行数、プロジェクトの数など、プロジェクトの定量的なメトリクスに焦点を当てがちです。プロジェクトの健全性を評価するために何を測定すべきかについては次のセクションで議論しますが、これらの数値を厳密に測定することよりも、オープンソース プログラムの成功を評価する他の多くの重要な方法があり、まずはそれらについて紹介します。

> **「傾向を知らせる手段としてメトリクスを使用することは良いことだと思いますが、成功のための唯一の方法として、それのみで評価していると、トラブルにつながります。」**
> 
> [**Joe Beda**](https://twitter.com/jbeda) **– a founding engineer of Kubernetes at Google and Co-founder and CTO at Heptio**

Kubernetesは、GitHub上で最も速い速度で開発されているオープンソース プロジェクトの一つで、過去3年間で1,181社の2,760人の開発者から8万件以上のコミットを引き付けています。しかし、このプロジェクトはスタート当初から、その技術とそれを使用することにユーザーがエキサイトしたかどうかという見地からみて、成功を勝ち取ってきました。「いくつかのオープンソースのメトリクスによる評価ではありません。」とBedaは言います。

以下に、オープンソース プログラム オフィスで採用されている一般的な目標のいくつかと、プログラム マネージャーが、これらの目標のために、プログラムの全体的な進捗状況をトラッキングするために評価する代表的な方法を示します。これらの目標の一部は、それ自体を直接測定できませんが、プロセス、効率性、品質の向上に関連しています。いくつかのものは、調査の実施や、積極的、定期的に口頭や書面で評価を要請するような方法で測定可能です。（あなたのチームと話してみましょう。）

## 目標 ＃1 効率的かつ合法的なオープンソース コードの使用を保証する

これは組織がオープンソースに関わり始めたときの出発点です。まず、エンジニアリング部門がインフラにおいて、あるいは、製品やサービスの中で、あるいはその両方で多くのオープンソース ソフトウェアを使用していることに気づくでしょう。プログラム オフィスは、オープンソースの活用に関するポリシーと意思決定を一元管理し、そのオープンソースの使用状況をトラッキングし、組織がさまざまなオープンソース ライセンスの下で法的義務を遵守することを手助けします。プログラム オフィスは、開発者が遭遇した法的問題を解決するために、どれだけ役立っているかをトラッキングすることもできます。

この第1の目標に対する、最も一般的な評価方法は、ポリシーとプロセスが意図したとおりに働いていること、および、組織が法令遵守を維持していることを確認することを狙っています。

- どの程度オープンソース コードを使用しているか。
- オープンソースの使用についてどの程度正確にトラッキングされているか。
- オープンソース コード使用に対するポリシーは明確で、開発者はそれを認識している。
- コードを取り込むためのプロセスとツールは明確で、開発者はそれに従っている。
- サードパーティのコードが使用されている製品とサービスはどれか。
- 現時点でコンプライアンスの問題はいくつあるか、どれほど迅速に解決されているか。
（コンプライアンス プログラムを持っていますか？このトピックの詳細については、私たちが提供している法務関連情報、「[Open Compliance Program](https://compliance.linuxfoundation.org/)」を参照してください。）

## 目標 ＃2 開発者の生産性の向上

オープンソースの使用をトラッキングし、管理し始めると、開発者のためにオープンソース プロジェクトへのコントリビューションがより簡単に行えるようにしてあげたくなるでしょう。あなたのエンジニアが、会社のビジネスが依存しているプロジェクトにバグフィックスや新機能を提出するために、融通のきかない手続きを経なければならないとすると、貴重な時間、リソースを浪費してしまいます。また、開発者は、時間の経過とともに技術的な負債が蓄積されてくるプロジェクトからフォークしたコードを保守するのではなく、アップストリームにコントリビューションすることによって長期的に多くの時間を節約することもできるようになります。

> **「私たちは、マラソン ルートに立ってランナーに水を与える人のようになろうとしています。私たちは開発者が自分たちのところに立ち寄るように促します。そうすることが、彼らが長距離走のゴールに到達する助けになるとわかっているからです。速度を減速させるためのスピード バンプではなく、サポート サービスになるように、オープンソース プログラムを設定しようとしているのです。」**
> 
> [**Gil Yehuda**](https://twitter.com/gyehuda) **– Senior Director of Open Source at Oath (Yahoo + AOL)**

この目標に関連するメトリクスは、開発者がオープンソース プロジェクトにコントリビューションすること、および、組織がアップストリームにコントリビューションする全体的なコード量を増やすことの円滑化を狙ったものです。コントリビューションの障壁を取り除き、承認プロセスを明確かつ迅速にすることにより、より多くのコントリビューションが効果的に行われることが期待できます。トラッキングするものは次のとおりです。

- 組織にとって戦略的であると位置づけられる外部プロジェクトに対するコミットの数
- コントリビューションしている開発者の数。また、誰が、どのプロジェクトに貢献しているか。
- 組織で働いているプロジェクト メンテナーの数（雇用された人、組織内で育てた人の内訳）
- コントリビューションしているプロジェクトの健全性
- センチメント分析（感情分析）：オープンソース コミュニティにおけるあなたの組織の評判
- 開発者はコントリビューション ポリシーを認識しているか。（あなたはポリシーを持っているはずですが。）
- 彼らはコントリビューションのためのプロセスに従っているか。（CLAに署名しなければならないなど）
- 彼らはあなたに助けを求めているか。速やかにサポートしているか。
- ソフトウェア リリース間隔 – 増加傾向か、減少傾向か。
- アップストリームへのコントリビューションに関連するエンジニアリング コストはどのようになっているか。フォークされたコードの保守のためのコストとの比較

## 目標 ＃3 オープンソース プロジェクトを創設、そして成長

これはFacebook社、Google社、Microsoft社、Twitter社などの技術系組織の多くのオープンソース プログラムが最重要目標にしているものです。彼らは困難な技術的問題を解決することを目指す数百（または数千）のオープンソース プロジェクトを創出しています。目標は、新しいアイデアをもたらし、より速いペースで技術を進歩させるくれる外部のユーザー、コントリビューターを引き付けることです。カリフォルニア大学バークレー校のHenry Chesbrough教授はこのコンセプトを[オープン イノベーション](https://hbr.org/2003/07/a-better-way-to-innovate)と呼んでいます。

> **「世界の優秀な人材に自分の会社で働いてもらうにはどうすればよいでしょう。そうです、まず自社製品をオープンソース化し、それから、自分のプロジェクトにコントリビューションしてくれるように彼らを説得するのです。」**
> 
> [**Chris Aniszczyk**](https://twitter.com/cra) **– Executive Director of the Open Container Initiative and COO of the Cloud Native Computing Foundation (and former head of open source programs at Twitter)**

プロジェクトの健全性を測定するために利用可能な多くのデータ ポイントは、この目標に対する状況をトラッキングするためのキーです（次のセクションのはじめの5項目を参照）。しかし、他にも同様に検討すべきデータ ポイントがあります。それは次のとおりです。

- 新しいオープンソース プロジェクトを設立するための明確なポリシーが存在し、開発者はそれを認識しているか。
- 新しいプロジェクトを立ち上げるための明確かつ容易なプロセスがあり、開発者はそれに従っているか。
- 外部の人があなたの組織のプロジェクトにコントリビューションするのは簡単か。
- プロジェクトのメンテナーは友好的で、みんなのためになっている
  - プロジェクトは十分に維持管理され、サポートされている
  - コードは十分に文書化されている
  - コントリビューションの方法は明確に定義されている
- 新しいコントリビューターの数、提起されたイシューの数、それをクローズするまでに要した時間など他の定量的なメトリクス（次のセクションを参照）
- あなたのプロジェクトが外部から受けとるコントリビューションの数や多様性
- あなたの組織のプロジェクトの人気度：GitHubのスター、ソーシャル メディアのフォロワーなど
- 導入や本番運用しているユーザーの数
- 組織が立ち上げるプロジェクトの数、利用層、品質など（例えば、モバイル分野、データ処理分野、インフラ関連プロジェクトなど）。
- プロジェクトおよび関連製品のパフォーマンスの向上度
- リリース間隔

## 目標 ＃4 開発者の採用と維持

組織としてオープンソース プロジェクトを立ち上げたり、参加したりすることは、開発者を引き付ける良い方法です。彼らは、トレーンイングもほとんど必要なしに、すぐにプロジェクトに参加できるでしょう。プロジェクトを活用したり、プロジェクトにコントリビューションしたりしている開発者は、組織に参加するときには、すでにプロセス、ツール、およびテクノロジに精通しているでしょう（本ガイド集の「[オープンソース デベロッパーの採用](https://www.linuxfoundation.jp/resources/open-source-guides/recruiting-open-source-developers/)」を参照）。

しかし、プログラム マネージャーが開発者の採用で直接的に役割を果たすわけでもないこともあるでしょう。また、あなたの組織のオープンソース参加が直接的に採用に影響を与えているのかについても、明らかではないかもしれません。オープンソース プログラムの取り組みと採用の関係をより直接的に結びつけるため、Facebook社は、新入社員に次の3つの基本的な質問を年2回のアンケートで行っています。

1. 同社のオープンソース プログラムを知っているか。
2. オープンソース プログラムを知っていることが会社に入社する意思決定にどのような影響を与えたか。
3. オープンソースでの経験は、今の仕事に生かされているか。

> **「私たちは、この調査で自分たちのオープンソース文化の健全性を評価します。この調査は、人々がオープンソース プロジェクトをどのように見ているかという総合的な有効性を示してくれます。数字が上向きであれば、うれしくなります。」**
> 
> [**Christine Abernathy**](https://twitter.com/abernathyca) **– Open Source Developer Advocate at Facebook**

開発者の採用に関するその他の一般的なメトリクスは以下のとおりです。

- 従業員はどのオープンソース プロジェクトを利用しているのか、どのプロジェクトにコントリビューションしているのか。
- 新入社員は組織をどのようにして知ったのか。
- オープンソース プロジェクトを通して、何名の開発者が採用できているのか。
- 何名のプロジェクトの メンテナーを採用し、育成できているのか。
- 新入社員が仕事をできるようになるまでの時間。
- オープンソースの開発者がどのようにしてキャリアを伸ばしているのか。
- 開発者によるコントリビューションは、仕事の成果の一部として評価されているか。
- 開発者は彼らのコントリビューションが認められて、報われているか。
- コントリビューションにおいて、開発者は支援やサポートが得られているか。

## 目標 ＃5 オープンソース文化のプロモーション

オープンソース プログラムが技術系の人材にいかに役立てるかは 、あなたの組織内におけるオープンソースの文化と実践の育成状況で多くが決まります。オープンソースを採用している組織は、開発者が仕事をし、大きく成長するための良い場所として知られているからです。オープンソース プログラム マネージャーは、コラボレーションのためのポリシーやその実践をつかさどるとともに、多くの場合、組織においてオープンソースの価値観をもたらす「大使」となっています。

オープンソース プログラムの効果を評価するために、あなたの組織でオープンソース文化がどのように進化しているかをトラッキングすることは重要です。オープンソース文化の浸透度を測定する一般的な方法としては以下があります。

- エンジニアリングからマーケティングや広報に至るまで、すべての部門の管理職層と個々のコントリビューターの間でオープンソースの戦略とオープンソース プログラムが認識され、サポートを受けている。
- オープンソース コミュニティにおけるブランド力と認知度 – あなたの組織がどのように認識されているか。
- 参加度 – あなたの企業が積極的にオープンソース コミュニティに参加しているか。
- トレーニングと指導 – 開発者と協力して、オープンソースへのコントリビューションとオープンソース プロジェクトを改善し、コントリビューションできる機会を見出し、オープンソース コミュニティのツールとプロセスを学び、それらによってコントリビューターが同僚やマネージャーからサポートを受けられるようにする。
- 一般的なツールセットの採用。
- コードの品質がオープンソース、外部利用可能のレベルにある
- 会議に出席して話したり、記事やチュートリアルを書いたりなど、組織を代表して、オープンソースのアドボケーター（支持代弁者）になっている。
- オープンソース組織、グループ、ハッカソンのスポンサーになる。

## 目標 ＃6 オープンソース コミュニティの向かう方向と製品戦略を一致させる

コミュニティの立場での アドボカシー（支持代弁）は、オープンソース プログラムの役割としては新しいものでしたが、急速に広がりつつあります。あなたのオープンソース コードを利用している外部のユーザーの声を、製品管理チームにフィードバックすることで、プロジェクトの開発者コミュニティとそれを利用しているユーザー コミュニティの架け橋としての役割を果たします。

これは、 あなたの企業が提供している製品やサービスがオープンソース コミュニティから恩恵を受け続け、その結果、オープンソース プログラムが組織の広範なビジネス戦略や目標に沿ったものとなることをより確かなものしていく重要な役割を果たします。アドボカシー活動が成功しているかをトラッキングするメトリクスのいくつかを以下に示します。

- 組織外からのコントリビューションの件数はどれくらいか。
- あなたの組織の外にはフルタイムのコントリビューターは何人いるか。
- 外部からのコントリビューションされたコードがどれくらい製品に含まれているか。
- オープンソース コントリビューターを何名雇用しているか。

セクション 5

## 何をトラッキングするのか

オープンソース プログラムの成功を評価したり、 進捗をトラッキングしたりする方法はたくさんあります。トラッキングするのはプロジェクトの健全性だけではありませんが、健全性をトラッキングすることは、やはり非常に重要です。問題は、オープンソース プロジェクトには利用可能なデータがあまりにも多く存在することです。データとして存在していれば、それを収集してトラッキングすることができます。また、各組織がどのようなメトリクスをトラッキングするか、それらをどのように扱うのかは、あなたのオープンソース プログラムの目標、市場やオープンソース コミュニティにおけるあなた独自の課題に大きく依存しています。

> **「データは存在していれば、可能な限り収集します。しかし、私たちは数字を得るためにデータを収集しているのではありません。私たちは、確実に、正しい成果を得るためにそれを収集しているのです。」**
> 
> [**Gil Yehuda**](https://twitter.com/gyehuda) **– Senior Director of Open Source at Oath (Yahoo + AOL)**

（完全に手順が自動化されていたり、病的な収集癖があったりする）プログラム マネージャーにとって、その答えはすべてのものをトラッキングすることです。しかし、特に大規模な組織では、すべてをトラッキングして、それらの意味を理解することが不可能なくらいプロジェクトが非常に多く存在します。オープンソース プロジェクトの健全性を評価するための本当の指標は何でしょうか。

ここでは、オープンソース プログラムのプロジェクトの全般的な健全性を評価するための最重要メトリクスを示します。これらは、より厳密で、示唆に富む分析を行う出発点にすぎません。これらは、複数のプロジェクトにたいして、健全性を確保する責任を持っているプログラム マネージャーを支援するための秘訣です。もちろん、個々のプロジェクト自身も、健全性評価のために専用のメトリクスをトラッキングする必要があります。オープンソースのメトリクスに関するGitHubのガイド（[GitHub&#39;s guide on open source metrics](https://opensource.guide/metrics/)）は、プロジェクトの メンテナーが注目すべき点について、優れた概要を説明してくれています。

これらのデータは、無償のオープンソース ツールや商用サービスを使用してGitHubから簡単に収集できます。定期的（毎月、四半期、毎年）にそれらを測定して、個々のプロジェクトの進捗をベンチマークするとともに、オープンソース プログラム全体としてもまとめます。管理職層へのレポートでそれらを使用したり、それらを開発者がプロジェクトを改善するために使用したりもします。

> **「プロジェクトが健全かどうか、私たちは定期的にチェックするようにしています。そして、彼らに改善すべき点についてアドバイスを与えるだけです。私たちは、直接的な管理は行いません。できるときに、あるいはしなければいけない時に、彼らにデータを与え、そっと改善を促すだけです。」**
> 
> [**Christine Abernathy**](https://twitter.com/abernathyca)   **– Open Source Developer Advocate at Facebook**

**コントリビューターの数（内部コントリビューションと外部コントリビューションの比率）**

プロジェクトの初期段階は、大部分のコントリビューションは内部開発者でなされます。その後、ソースコードが使用またはフォークされるにつれて、より多くの外部からのコントリビューションを含むように進化していきます。時間が経っても安定的に継続している最も健全なプロジェクトは、非常に多様性のあるコミュニティを持っており、そこでは、そのコードがビジネスに直結しているプロジェクト エコシステム内の企業から多くのコントリビューションを受けています。（Kubernetesは1000以上の企業からコントリビューションを受けています。）

新しい外部コントリビューターを常に引き付けているプロジェクトは、プロジェクトを維持し、コントリビューターを歓迎し、コミュニティからのフィードバックを取り入れる良い仕事をしている可能性が高いようです。（注：これは、コントリビューターの総数が増加していないプロジェクトでも当てはまるようです。）

 ![](https://www.linuxfoundation.jp/wp-content/uploads/2017/09/Kubernetes-contributors.png)

プルリクエストで、サブミットされたもの、オープンな状態のもの、および、受け入れられたものの数（また、それらがオープンであった時間）

コントリビューターがバグを見つけたり、あるいは、自ら（パッチ作成の許可を得て）パッチやコードを作って機能要求を行ったりする時に、プルリクエストとして、それをサブミットします。プルリクエストの数とそれらの状況をトラッキングすることは、あなたの会社の従業員以外のコントリビューターによって、どれだけのコードが提供されたかがわかるので、プロジェクトにおける外部の関心の高さをはかるための指標になります。

 
 ![](https://www.linuxfoundation.jp/wp-content/uploads/2017/09/Kubernetes-pull-requests.png)

プルリクエストがオープンの状態の時間の長さは、あなたのプロジェクトの メンテナーが外部のコントリビューターに、いかに早く対応し、彼らを喜んで迎えているかを示します。プルリクエストに応答がなく、それが長時間放置されると、潜在的な力を持ったコントリビューターは、彼らの良いアイデアを他の場所で実現することになるかもしれません。

> **「良いプロジェクトは、おそらく2〜3か月以上プルリクエストをオープンの状態で放置しないでしょう。残念ながら実際にはたくさんありますが。」**
> 
> [**Christine Abernathy**](https://twitter.com/abernathyca)  **– Open Source Developer Advocate at Facebook**

これらのメトリクスはプロジェクトの規模に大きく依存していることを心に留めて置いてください。Facebook社の小規模なプロジェクトは、オープンな状態のプルリクエスト数を10以下に抑えるように努力しています。しかし、プルリクエストを10以下に保つことは、 メンテナーの数に比べ、コミュニティのインプットが非常に多い大規模なプロジェクトにとっては難しいでしょう。これらのプルリクエストをレビューするには時間がかかるので、大規模プロジェクトではオープンな状態の長いプルリクエストが存在するようになる傾向があります。

Facebook社のオープンソース オフィスでは、頻繁にデータベースを検索し、オープンな状態のプルリクエストが最も多い上位5つのプロジェクトを選定しています。彼らはいくつかの問題点を特定して、プロジェクトの メンテナーと議論を始めます。彼らは問題の根本原因を特定し、問題解決を促進するために、彼らに2、3の質問をします。多くの場合、コミュニティに注意をはらい、コミュニティが幸せである状態を保つことが重要であることを再確認させるという簡単なものです。しかし時には、数字を深く分析し、プロジェクトの深い問題を指摘することもあります。多量のオープンな状態のプルリクエスト、古いプルリクエストの存在は、わずか1〜2人でプロジェクトを維持していることを示している場合があります。これは潜在的な赤信号です。

**サブミットされたイシューの数（また、それらがオープンであった時間）**

プルリクエストをサブミットするための時間、権限、またはその技術を持ってないけれども、プロジェクトのコードに問題が発生したユーザーは、バグや機能要求をイシューとしてサブミットする可能性があります。イシューの数と、それにどのように対応しているかは、どの程度プロジェクトがユーザーに採用されているかと、 メンテナーがユーザーのニーズに対して、いかに早く対応しているかを示してくれます。

この数は、もちろん、イシューのトラッキング方法によって異なります。GitHubをバグのトラッキングのみのために使用しているプロジェクトは、機能要求を含むイシューに対してもGitHubを使用しているプロジェクトと比較するとイシューがオープン状態である時間ははるかに短いでしょう。これらの違いで、イシューの滞在時間は短くなったり、長くなったりします。

 ![](https://www.linuxfoundation.jp/wp-content/uploads/2017/09/Kubernetes-issues.png)


**コントリビューターあたりのコミット数（外部と内部の比較）**

プロジェクトの総コミット数に対する、外部からのコミット数の比率は、外部から新しいアイデアを得るという、オープンな環境におけるイノベーションによって、プロジェクトがいかに成果を上げているかを示す指標になります。健全なプロジェクトでは、時間の経過と共に外部コントリビューターの割合が増えてきます。コントリビューターごとのコミット数を測定することは、あなたのプロジェクトが新しいコントリビューターを引き付けているかどうか、そして新しいコントリビューターがコントリビューションを継続してくれているかを評価するのにも役立ちます。

**外部のプロジェクト利用者数**

オープンソース プロジェクトごとに、本番環境でそのソフトウェアを採用している組織をトラッキングする方法が必要です。ADOPTERS.mdファイルやREADMEの中のシンプルなリストを通して調べる場合でも、重要なのはこのリストをトラッキングし、時間の経過と共に採用者が増加していることを確認することです。外部利用者の数の増加が止まり、減少していると、それはプロジェクトが成熟した状態から衰退への道を歩み始めたというシグナルです。

**作成したプロジェクトや、コントリビューションしているプロジェクトの数（オープンソース プログラム全体に渡って）**

あなたの組織がリリースするプロジェクトごとにこれらのメトリクスをトラッキングするだけでなく、あなたの組織の開発者が積極的にコントリビューションしているプロジェクトもトラッキングします。オープンソース戦略を作成するプロセスでは、組織が使用しているビジネス上重要なプロジェクトを特定し、それらのプロジェクトにコントリビューションするために一定の投資を実施したはずです。組織のオープンソースの成功を、自身のオープンソース プロジェクトの健全性だけでなく、オープンソース活動全体で測ることも重要です。これには、あなたの会社の製品開発やビジネスオペレーションが依存しているプロジェクトの健全性だけでなく、使用したり、リリースしたりしているすべてのプロジェクトがオープンソース ライセンスに法的に準拠していることを確認することも含まれます（[Open Compliance Program publications](https://compliance.linuxfoundation.org/references/compliance-related-publications)を参照）。

セクション 6

## トラッキングすべきその他のメトリクス

基本的なプロジェクト メトリクスは、あなたのオープンソースへのコントリビューションの実情を正確に把握するための第一歩になります。しかし、プログラム マネージャーとして成功するためには、他の重要なメトリクスに対しても深い洞察が求められます。

トラッキング可能なもの、また、トラッキングすべきものが他にもたくさんあり、以下に紹介します。あなたの目標に合わせて採用してください。数値そのものは目標ではないことを再度心に留めて置いてください。プロジェクトやプロセスが改善されていることを知らせてくれるのは、時間をかけてトラッキングし、パターンをデータの中に見つけるプロセスなのです。プロジェクトごとにも、また、プロジェクト全体に渡っても測定し、あなたのオープンソース プログラムの成果と結果を全体的に評価します。

- 人気度 / 認知度
  - プロジェクトのWebサイト訪問者
  - GitHub / GitLabでのフォロワー総数
  - Twitter、Facebook、LinkedInなどのソーシャル メディア アカウントのフォロワー数
  - ニュースクリップやメディアでの言及
  - 設定したり、ホスティングされたりしているミートアップの数（たとえば、meetup.com経由）
- 影響度
  - あなたの戦略的プロジェクトで メンテナー、リーダーシップの役割をしている従業員の数
  -  あなたのプロジェクトへのコントリビューターの多様性
  - 拒否されたパッチとその理由
  - 採用されている状況
  - ダウンロード数
  - 作成されたフォークの数
  - コントリビューションしてくれている外部企業の数
  - 導入段階（POCおよび本番環境での導入数）
  - 企業のビジネスを支えているもの（製品）の数と質 – これは、あなたのプロジェクトにコントリビューションしている企業を調べたり、ニュースや業界誌の報道をフォローしたりしてトラッキングできます。
- プログラムの費用
  - スタッフ：エンジニアリング、広報、マーケティング、法務
  - インフラとサポート
  - ツール
  - 会議出席と出張
  - トレーニング
  - メンバーシップの会費、寄付

セクション 7

## 結論

組織は、オープンソース プログラム、プロジェクト、コントリビューションを、彼らのニーズに最も合った方法で評価します。覚えておくべき最も重要なことは、それを達成するための戦略と段階的な目標を設定することです。そうすれば、あなたが何をトラッキングするのか、それをどのようにトラッキングするかは自然と分かるようになります。