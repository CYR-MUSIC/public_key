# 弊社のPGP公開鍵について
公開日: 2023年4月12日


弊社では、皆様がセキュリティ関係の報告時の連絡をする際の暗号化等の目的でPGP鍵を公開しています。


## PGP鍵の運用方針
・ルート鍵は、用途別鍵を署名するためにのみ用います。有効期限は無期限とします。

・用途別鍵は、部署や用途毎に用いるもので、原則として有効期限を1年とします。ただし、用途によっては1年以上を有効期限とする場合もあります。

・毎年更新される年度鍵は、ルート鍵によって署名します。 そのため、利用者はルート鍵を一度慎重に確認し信用すると、PGP の信用の輪の仕組みによって自動的に年度鍵が確認されることになります。

## PGP鍵
弊社から発行される鍵は全て [keys.openpgp.org](keys.openpgp.org) から取得することが可能です。
### [ルート鍵](https://keys.cyrmusic.net/root.asc)
```
鍵タイプ: ed25519 
有効期限: never
フィンガープリント: A423 EE7B 00BC 9A3A 8F93  279E 79DE BC7D D537 A8A2
ユーザーID: CYR MUSIC LLC Root <info@cyrmusic.com>
```
・有効期限が無い署名専用の鍵です。

### [セキュリティ関連の報告用鍵](https://keys.cyrmusic.net/security.asc)
```
鍵タイプ: cv25519 
有効期限: 2024-04-11
フィンガープリント: B906 0AF6 933C 1589 2DDA  AD2D F626 B7ED 532A 8266
ユーザーID: CYR MUSIC LLC Security <security@cyrmusic.com>
```
・有効期限1年で、セキュリティ関係のご連絡の暗号化に用いることができる鍵です。

・セキュリティ関係のご連絡は security@cyrmusic.com までお願いいたします。
