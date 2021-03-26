# Chapter2
## 2-3
### justify-content
* https://developer.mozilla.org/ja/docs/Web/CSS/justify-content

```
justify-content: center;     /* アイテムを中央に寄せる */
justify-content: start;      /* アイテムを先頭に寄せる */
justify-content: end;        /* アイテムを末尾に寄せる */
justify-content: flex-start; /* フレックスアイテムを先頭に寄せる */
justify-content: flex-end;   /* フレックスアイテムを末尾に寄せる */
justify-content: left;       /* アイテムを左端に寄せる */
justify-content: right;      /* アイテムを右端に寄せる */

/* 通常の配置 */
justify-content: normal;

/* 均等配置 */
justify-content: space-between; /* 各アイテムを均等に配置し
                                   最初のアイテムは先頭に寄せ、
                                   最後のアイテムは末尾に寄せる */
justify-content: space-around;  /* 各アイテムを均等に配置し
                                   各アイテムの両側に半分の大きさの
                                   間隔を置く */
justify-content: space-evenly;  /* 各アイテムを均等に配置し
                                   各アイテムの周りに同じ大きさの間隔を置く */
justify-content: stretch;       /* 各アイテムを均等に配置し
                                   サイズが 'auto' であるアイテムは、
                                   コンテナーに合わせて引き伸ばす */

/* あふれた場合の配置 */
justify-content: safe center;
justify-content: unsafe center;

/* グローバル値 */
justify-content: inherit;
justify-content: initial;
justify-content: unset;
```

### flexについて
https://www.w3.org/TR/css-flexbox/#box-model
