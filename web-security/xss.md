- 仅用 []()+! 就足以实现几乎任意Javascript代码 http://www.cnblogs.com/pandora/archive/2010/02/27/1674833.html
- 突破XSS字符数量限制执行任意JS代码 http://netsecurity.51cto.com/art/200905/122792.htm
- Bypass XSS Cloudflare Filter on INDODAX.com https://medium.com/@denyfebriant/bypass-xss-filter-cloudflare-on-indodax-com-526fb32ffa08

## UXSS(->BrowserSec)

Universal Cross-Site Scripting，通用跨站脚本攻击。

UXSS利用浏览器或者浏览器扩展漏洞来制造产生XSS的条件并执行代码。

UXSS对于攻击发起时浏览器打开或缓存的所有页面（即使不同域）的会话信息都可以进行访问。

* [通用跨站脚本攻击(UXSS)](http://www.fooying.com/uxss/)
* [Chrome 扩展安全研究: 一个UXSS的挖掘经历](https://www.anquanke.com/post/id/98917)

## XSS Exercise
- alert(1) to win https://alf.nu/alert1
- prompt(1) to win http://prompt.ml/0


