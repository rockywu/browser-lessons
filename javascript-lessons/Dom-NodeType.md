### nodeType介绍

节点类型 | 节点名| nameConstant |nodeName返回 | nodeValue返回 | 描述 |子节点
:---:|:---: | :---: | :---: | :---: | :---: | :---:
1 | Element | ELEMENT_NODE | 元素名 | null | 代表元素 | Element, Text, Comment, ProcessingInstruction, CDATASection, EntityReference
2 | Attr | ATTRIBUTE_NODE | 属性名 | 属性值 | 代表属性 | Text, EntityReference
3 | Text | TEXT_NODE | #test | 节点的内容 | 代表元素或属性中的文本内容 | None
4 | CDATASection | CDATA_SECTION_NODE | #cdata-section | 节点的内容 | 代表文档中的 CDATA 部分（不会由解析器解析的文本）| None
5 | EntityReference | ENTITY_REFERENCE_NODE | 实体引用名称 | null | 代表实体引用 | Element, ProcessingInstruction, Comment, Text, CDATASection, EntityReference
6 | Entity | ENTITY_NODE | 实体名称	| null | 代表实体 | Element, ProcessingInstruction, Comment, Text, CDATASection, EntityReference
7 | ProcessingInstruction | PROCESSING_INSTRUCTION_NODE | target | 节点的内容 | 代表处理指令 | None
8 | Comment | COMMENT_NODE | #comment | 注释文本 | 代表注释 | None
9 | Document | DOCUMENT_NODE | #document | null | 代表整个文档（DOM 树的根节点） | Element, ProcessingInstruction, Comment, DocumentType
10| DocumentType | DOCUMENT_TYPE_NODE | 文档类型名称 | null | 向为文档定义的实体提供接口 | None
11| DocumentFragment | DOCUMENT_FRAGMENT_NODE | #document片段 | null | 代表轻量级的 Document 对象，能够容纳文档的某个部分 | Element, ProcessingInstruction, Comment, Text, CDATASection, EntityReference
12| Notation | NOTATION_NODE | 符号名称 | null | 代表 DTD 中声明的符号 | None