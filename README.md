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

### git管理課のファイルをロード

![](sandbox.drawio.svg)


### draw.io経由でロード(現在機能していない)

https://zenn.dev/bigwheel/articles/b56feed09a3732

[![](sandbox.drawio.svg)](https://app.diagrams.net/#Hlig-noppy%2Fsandbox-doc%2Fdoc%2Fsandbox.drawio.svg)

[draw.ioリンク](https://app.diagrams.net/#Hlig-noppy%2Fsandbox-doc%2Fdoc%2Fsandbox.drawio.svg#%7B%22pageId%22%3A%22qb4v2cUt2ur6bKFO8C9D%22%7D)

### Embed a self-editing SVG image in GitHub markdown

sandbox.drawio.svg
