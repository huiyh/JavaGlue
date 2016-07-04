# JavaGlue
Java静态注入框架
现有的Java依赖注入框架，都采用非静态方式，在Android多Dex的场景下表现不佳。
为适应Android中dex拆分的需求，减少类数量和依赖关系， 采用静态注入的方式。
