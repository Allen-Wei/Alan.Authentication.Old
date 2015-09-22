# Alan.Authentication.Old
Alan.Authentication 的老版本, 主要使用了 `HttpContext.Current` 对象. 而 `HttpContext.Current` 对象与 `System.Web.dll` 是紧耦合的, 在[Alan.Authentication](https://github.com/Allen-Wei/Alan.Authentication)里去除了 `HttpContext.Current` 的依赖.
