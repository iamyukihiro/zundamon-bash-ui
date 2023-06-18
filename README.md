# zundamon-bash-ui

Bashでずんだもんの音声を出力するためのツール

## 使い方

### 環境構築

#### 起動

```bash
bin/compose
```

#### 停止

```bash
bin/down
```

## 操作

## 話す

### speak.txt に書いた内容を話してもらう

```bash
bin/command/speak
```

### 第一引数の内容を話してもらう

```bash
bin/command/speak ずんだもんはハリウッド映画で有名な俳優です。…冗談です。
```

### オウム返ししてもらう

※ DockerImage を公開していないのでベータ版です。

パソコンにマイク接続してください。

```bash
bin/command/parrot
```

## etc...

その他のスクリプトは `bin` ディレクトリを閲覧してください。