# sandbox-doc

github markdown, wiki, draw.ioなどの動作確認用

publicリポジトリ


## mermaid.js

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```


## plantUML

```plantuml
@startuml

[*] --> State1
State1 --> [*]
State1 : this is a string
State1 : this is another string

State1 -> State2
State2 --> [*]

@enduml
```

PlantUML.com経由で画像化は可能  
![PlantUML.com経由で画像化は可能](https://www.plantuml.com/plantuml/svg/SoWkIImgAStDuOhMYbNGrRLJ22v9B4arv89GO16W38nhfL2IaLci04I92iKbHPbvwLXayl9BCbABOF8m1J2ZZRWW5DneXzIy5A030000)



## draw.io

<!--
通常の画像表示
![](sandbox.drawio.svg)

通常のリンク
[draw.ioでGithubファイルを開くリンク](https://app.diagrams.net/#Hlig-noppy%2Fsandbox-doc%2Fdoc%2Fsandbox.drawio.svg)
-->

<!-- 画像表示 + draw.ioでGithub上のファイルを開くリンク(要 各自での認証連携) -->
[![](sandbox.drawio.svg)](https://app.diagrams.net/#Hlig-noppy%2Fsandbox-doc%2Fdoc%2Fsandbox.drawio.svg)
