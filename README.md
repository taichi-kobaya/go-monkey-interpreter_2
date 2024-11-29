# Go言語でつくるインタプリタ学習用

## １章　字句解析

### 1.2　トークンを定義する

- type TokenType stringはstring型のエイリアスとしてTokenTypeを定義している
    - Token構造体のTypeをstringにしても機能的には問題ないが以下の理由でTokenTypeにしている
        - 意味を明確にするため
        - コードの可読性を向上させるため
        - 型の変更に対応しやすい
