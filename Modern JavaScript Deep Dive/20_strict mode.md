# **20 strict mode**

- [**20 strict mode**](#20-strict-mode)
  - [**ë¤ì´ê°ë©° ð**](#ë¤ì´ê°ë©°-)
  - [**strict modeë?**](#strict-modeë)
  - [**strict modeì ì ì©**](#strict-modeì-ì ì©)
  - [**ì ì­ì strict modeë¥¼ ì ì©íë ê²ì í¼íì**](#ì ì­ì-strict-modeë¥¼-ì ì©íë-ê²ì-í¼íì)
  - [**í¨ì ë¨ìë¡ strict modeë¥¼ ì ì©íë ê²ë í¼íì**](#í¨ì-ë¨ìë¡-strict-modeë¥¼-ì ì©íë-ê²ë-í¼íì)
  - [**strict modeê° ë°ììí¤ë ìë¬**](#strict-modeê°-ë°ììí¤ë-ìë¬)
  - [**strict mode ì ì©ì ìí ë³í**](#strict-mode-ì ì©ì-ìí-ë³í)
    - [**ì¼ë° í¨ìì this**](#ì¼ë°-í¨ìì-this)
    - [**arguments ê°ì²´**](#arguments-ê°ì²´)


<br>

## **ë¤ì´ê°ë©° ð**

ë³¸ ì ë¦¬ê¸ì ì´ìëª¨ê°ì¬ëì ëª¨ë ìë°ì¤í¬ë¦½í¸ Deep Diveë¥¼ ê³µë¶íê³  ìµëíê¸° ìí´ ì  ëë¦ëë¡ ì ë¦¬í ê¸ ìëë¤. ë³´ë¤ ìì¸í ì ë³´ë¥¼ ìíì ë¤ë©´ í´ë¹ ìì ì ì°¸ê³ íìê¸¸ ë°ëëë¤.

<br>

## **strict modeë?**

ES5ì ì¶ê°ë `strict mode`(ìê²© ëª¨ë)ë ìë°ì¤í¬ë¦½í¸ ì¸ì´ì ë¬¸ë²ì ì¢ ë ìê²©í ì ì©íì¬ ì¤ë¥ë¥¼ ë°ììí¬ ê°ë¥ì±ì´ ëê±°ë ìë°ì¤í¬ë¦½í¸ ìì§ì ìµì í ììì ë¬¸ì ë¥¼ ì¼ì¼í¬ ì ìë ì½ëì ëí´ ëªìì ì¸ ìë¬ë¥¼ ë°ììí¨ë¤.

ESLint ê°ì ë¦°í¸ ëêµ¬ë¥¼ ì¬ì©í´ë ì ì¬í í¨ê³¼ë¥¼ ì»ì ì ìëë°, ì ì  ë¶ì ê¸°ë¥ì íµí´ ìì¤ì½ëë¥¼ ì¤ííê¸° ì ì ìì¤ì½ëë¥¼ ì¤ìºíì¬ ë¬¸ë²ì  ì¤ë¥ë§ì´ ìëë¼ ì ì¬ì  ì¤ë¥ê¹ì§ ì°¾ìë´ê³  ì¤ë¥ì ìì¸ì ë¦¬í¬íí´ì£¼ë ì ì©í ëêµ¬ë¤.

<br>

---

## **strict modeì ì ì©**

ì ì­ì ì ë ëë í¨ì ëª¸ì²´ì ì ëì `'use strict';` ë¥¼ ì¶ê°íë¤. ì ì­ì ì¶ê°íë©´ ì¤í¬ë¦½í¸ ì ì²´ì ì ì©ëë¤.

<br>

---

## **ì ì­ì strict modeë¥¼ ì ì©íë ê²ì í¼íì**

strict mode ì¤í¬ë¦½í¸ì non-strict mode ì¤í¬ë¦½í¸ë¥¼ í¼ì©íë ê²ì ì¤ë¥ë¥¼ ë°ììí¬ ì ìë¤. í¹í ì¸ë¶ ìëíí° ë¼ì´ë¸ë¬ë¦¬ë¥¼ ì¬ì©íë ê²½ì° ë¼ì´ë¸ë¬ë¦¬ê° non-strict modeì¸ ê²½ì°ë ìê¸° ëë¬¸ì ì ì­ì strict modeë¥¼ ì ì©íë ê²ì ë°ëì§íì§ ìë¤. ì´ë¬í ê²½ì° ì¦ì ì¤í í¨ìë¡ ì¤í¬ë¦½í¸ ì ì²´ë¥¼ ê°ì¸ì ì¤ì½íë¥¼ êµ¬ë¶íê³  ì¦ì ì¤í í¨ì ì ëì strcit modeë¥¼ ì ì©íë¤.

<br>

---

## **í¨ì ë¨ìë¡ strict modeë¥¼ ì ì©íë ê²ë í¼íì**

í¨ì ë¨ìë¡ strict modeë¥¼ ì ì©í  ìë ìë¤. ì´ë¤ í¨ìë ì ì©íê³ , ì´ë¤ í¨ìë ì ì©íì§ ìë ê²ì ë°ëì§íì§ ìì¼ë©° ë²ê±°ë¡­ë¤. ëí, strict modeê° ì ì©ë í¨ìê° ì°¸ì¡°í  í¨ì ì¸ë¶ì ì»¨íì¤í¸ì strict modeë¥¼ ì ì©íì§ ìëë¤ë©´ ë¬¸ì ê° ë°ìí  ì ìë¤.

<br>

---

## **strict modeê° ë°ììí¤ë ìë¬**

- ### **ìë¬µì  ì ì­**

  ì ì¸íì§ ìì ë³ìë¥¼ ì°¸ì¡°íë©´ `ReferenceError`ê° ë°ìíë¤.

- ### **ë³ì, í¨ì, ë§¤ê°ë³ìì ì­ì **

  `delete` ì°ì°ìë¡ ë³ì, í¨ì, ë§¤ê°ë³ìë¥¼ ì­ì íë©´ `SyntaxError`ê° ë°ìíë¤.

- ### **ë§¤ê°ë³ì ì´ë¦ì ì¤ë³µ**

  ë°ë³µë ë§¤ê°ë³ì ì´ë¦ì ì¬ì©íë©´ `SyntaxError`ê° ë°ìíë¤.

- ### **with ë¬¸ì ì¬ì©**
  with ë¬¸ì ì¬ì©íë©´ `SyntaxError`ê° ë°ìíë¤. `with` ë¬¸ì ì ë¬ë ê°ì²´ë¥¼ ì¤ì½í ì²´ì¸ì ì¶ê°íë¤. `with` ë¬¸ì ì±ë¥ê³¼ ê°ëì±ì´ ë®ìì ¸ ì¬ì©íì§ ìë ê²ì´ ì¢ë¤.

<br>

---

## **strict mode ì ì©ì ìí ë³í**

### **ì¼ë° í¨ìì this**

strict modeìì í¨ìë¥¼ ì¼ë° í¨ìë¡ì í¸ì¶íë©´ `this`ì `undefined`ê° ë°ì¸ë© ëë¤. ìì±ì í¨ìê° ìë ì¼ë° í¨ì ë´ë¶ììë `this`ë¥¼ ì¬ì©í  íìê° ìê¸° ëë¬¸ì´ë¤.

### **arguments ê°ì²´**

strict modeììë ë§¤ê°ë³ìì ì ë¬ë ì¸ìë¥¼ ì¬í ë¹íì¬ ë³ê²½í´ë arguments ê°ì²´ì ë°ìëì§ ìëë¤.

```javascript
(function (a) {
  'use strict';
  // ë§¤ê°ë³ìì ì ë¬ë ì¸ìë¥¼ ì¬í ë¹íì¬ ë³ê²½
  a = 2;

  // ë³ê²½ë ì¸ìê° arguments ê°ì²´ì ë°ìëì§ ìëë¤
  console.log(arguments); // { 0: 1, length: 1 }
})(1);
```


