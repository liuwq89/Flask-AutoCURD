# Flask-AutoCURD

## Project Description
Designed and implemented a reusable API framework CommonResource based on Flask-RESTful. The base class provides default CRUD operations, allowing business modules to generate five standard REST API endpoints simply by inheriting the class and binding the corresponding model, significantly reducing repetitive code.

The framework also offers extensible hook functions to support custom logic such as relational queries, data preprocessing, and field enrichment. Subclasses can override these hooks as needed to tailor or extend the default behavior, enabling highly flexible and maintainable API customization.


## 项目描述（Description）

基于 Flask-RESTful 设计并实现了一个可复用的通用接口框架 CommonResource。在基类中预置了标准的 CRUD 默认逻辑，业务模块只需继承该类并绑定对应的 Model，即可自动生成包含五类操作的通用 REST API 接口，大幅减少重复代码量。

框架同时提供 可扩展的钩子函数（Hook Functions），用于处理如关联查询、数据清洗、字段扩展等特殊逻辑。子类只需按需实现对应钩子，即可覆盖或增强默认行为，实现高灵活性的接口定制能力。


