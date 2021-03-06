## Authors
Gabriel Nunes∗, Jairo Souza∗, Baldoino Fonseca∗, Marcio Ribeiro∗ and Alessandro Garcia†\
∗Computing Institute, Federal University of Alagoas (UFAL), Brazil\
†Opus Research Group – LES, Informatics Dept., PUC-Rio, Brazil\

## Abstract

During the evolution of a software, developers perform changes that may lead to the introduction of bugs. Hence, it is important to better understand the bug-introducing changes, as well as which kinds of changes, are more related to the introduction of bugs. Recent studies investigated the relation between changes and bugs. However, they consider only single changes rather than the software changes history. In our study, we investigate the relation between the history of changes and the introduction of bugs. We collected 4,613 bugs introduced along the history of 303,068 methods from 12 open-source systems. The results indicate that the majority of the investigated methods contain a long history to be analyzed; the longer the changes in methods, higher is the density of bugs introduced; additions are more prone to introduce bugs than deletion; and changes involving method calls and statements have a higher influence to introduce bugs. 


## Groups Table

| Acronym  | Group Name                       | Metrics                         |  
|-------------------|----------------------------------|----------------------------------|
| NOCN              | Number of Conditions             | IF_STATEMENT, SWITCH_STATEMENT, SWITCH_CASE                  | 
| NOL               | Number of Loops                | FOR_STATEMENT, WHILE_STATEMENT, DO_STATEMENT, ENHANCED_FOR_STATEMENT | 
| NOMC              | Number of Method Calls           | METHOD_INVOCATION, SUPER_METHOD_INVOCATION, SUPER_CONSTRUCTOR_INVOCATION, CONSTRUCTOR_INVOCATION   |     
| NOMD              | Number of Method Declarations    | METHOD_DECLARATION              | 
| NOV               | Number of Variable Declarations  | VARIABLE_DECLARATION_EXPRESSION, SINGLE_VARIABLE_DECLARATION |       
| NOA               | Number of Assignments            | ASSIGNMENT                      | 
| NCO               | Number of Condtional Expressions | CONDITIONAL_EXPRESSION          |                              
| NOAR              | Number of Arrays                 | ARRAY_ACCESS, ARRAY_CREATION, ARRAY_INITIALIZER |   
| NOIP              | Number of Imports                | IMPORT_DECLARATION              |                                     
| NOO               | Number of Object Instantiations  | CLASS_INSTANCE_CREATION         |                              
| NES               | Number of Enumeration Statements | ENUM_CONSTANT_DECLARATION, ENUM_DECLARATION            |     
| NOE               | Number of Expressions            | CAST_EXPRESSION, INFIX_EXPRESSION, LAMBDA_EXPRESSION, INSTANCEOF_EXPRESSION, POSTFIX_EXPRESSION, PREFIX_EXPRESSION, THIS_EXPRESSION, PARENTHESIZED_EXPRESSION, INTERSECTION_TYPE |
| NOES              | Number of Exceptions             | CATCH_CLAUSE, THROW_STATEMENT, TRY_STATEMENT                |    
| NOLI              | Number of Literals               | BOOLEAN_LITERAL, CHARACTER_LITERAL, NUMBER_LITERAL, STRING_LITERAL, TYPE_LITERAL, NULL_LITERAL      |  
| NOBS              | Number of Branching Statements   | CONTINUE_STATEMENT, BREAK_STATEMENT, RETURN_STATEMENT          |  
| NOF               | Number of Fields                 | FIELD_ACCESS, SUPER_FIELD_ACCESS, FIELD_DECLARATION            | 
| NOAN              | Number of Annotations            | MARKER_ANNOTATION,NORMAL_ANNOTATION, ANNOTATION_TYPE_DECLARATION, SINGLE_MEMBER_ANNOTATION |             
| NOJ               | Number of JavaDocs               | JAVADOC              |      
| NOPD              | Number of Packages               | PACKAGE_DECLARATION  |        
| NOMR              | Number of Method References      | CREATION_REFERENCE, SUPER_METHOD_REFERENCE, EXPRESSION_METHOD_REFERENCE, TYPE_METHOD_REFERENCE     |
| NOS               | Number of Statements             | EXPRESSION_STATEMENT            |       

## Change Metrics

1. ANNOTATION_TYPE_DECLARATION        
2. ANNOTATION_TYPE_MEMBER_DECLARATION 
3. ANONYMOUS_CLASS_DECLARATION
4. ARRAY_ACCESS
5. ARRAY_CREATION
6. ARRAY_INITIALIZER
7. ARRAY_TYPE
8. ASSERT_STATEMENT
9. ASSIGNMENT
10. BLOCK_COMMENT
11. BOOLEAN_LITERAL
12. BREAK_STATEMENT
13. CAST_EXPRESSION
14. CATCH_CLAUSE
15. CHARACTER_LITERAL
16. CLASS_INSTANCE_CREATION
17. CONDITIONAL_EXPRESSION
18. CONSTRUCTOR_INVOCATION
19. CONTINUE_STATEMENT
20. CREATION_REFERENCE
21. DIMENSION
22. DO_STATEMENT
23. EMPTY_STATEMENT
24. ENHANCED_FOR_STATEMENT
25. ENUM_CONSTANT_DECLARATION
26. ENUM_DECLARATION
27. EXPRESSION_METHOD_REFERENCE
28. EXPRESSION_STATEMENT
29. FIELD_ACCESS
30. FIELD_DECLARATION
31. FOR_STATEMENT
32. IF_STATEMENT
33. IMPORT_DECLARATION
34. INFIX_EXPRESSION
35. INITIALIZER
36. INSTANCEOF_EXPRESSION
37. INTERSECTION_TYPE
38. JAVADOC
39. LABELED_STATEMENT
40. LAMBDA_EXPRESSION
41. LINE_COMMENT
42. MARKER_ANNOTATION
43. MEMBER_REF
44. MEMBER_VALUE_PAIR
45. METHOD_DECLARATION
47. METHOD_INVOCATION
48. METHOD_REF_PARAMETER
49. METHOD_REF
50. MODIFIER
51. NAME_QUALIFIED_TYPE
52. NORMAL_ANNOTATION
53. NULL_LITERAL
54. NUMBER_LITERAL
55. PACKAGE_DECLARATION
56. PARAMETERIZED_TYPE
57. PARENTHESIZED_EXPRESSION
58. POSTFIX_EXPRESSION
59. PREFIX_EXPRESSION
60. PRIMITIVE_TYPE
61. QUALIFIED_NAME
62. QUALIFIED_TYPE
63. RETURN_STATEMENT
64. SIMPLE_NAME
65. SIMPLE_TYPE
66. SINGLE_MEMBER_ANNOTATION
67. SINGLE_VARIABLE_DECLARATION
68. STRING_LITERAL
69. SUPER_CONSTRUCTOR_INVOCATION
70. SUPER_FIELD_ACCESS
71. SUPER_METHOD_INVOCATION
72. SUPER_METHOD_REFERENCE
73. SWITCH_CASE
74. SWITCH_STATEMENT
75. SYNCHRONIZED_STATEMENT
76. TAG_ELEMENT
77. TEXT_ELEMENT
78. THIS_EXPRESSION
79. THROW_STATEMENT
80. TRY_STATEMENT
81. TYPE_DECLARATION
82. TYPE_DECLARATION_STATEMENT
83. TYPE_LITERAL
84. TYPE_METHOD_REFERENCE
85. TYPE_PARAMETER
86. UNION_TYPE
87. VARIABLE_DECLARATION_EXPRESSION
88. VARIABLE_DECLARATION_FRAGMENT
89. VARIABLE_DECLARATION_STATEMENT
90. WHILE_STATEMENT
91. WILDCARD_TYPE


## Dataset
The entire data are stored in the Neo4j graph-oriented database (Version 2.3).
[Download Dataset Change Metrics](https://drive.google.com/file/d/1A5fDuZAR4nww1sAmVMLFoujFnSRxsFra/view?usp=sharing)
