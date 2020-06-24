# CONSTRUCTORS IN C#

### What is Constructor in c#?
- A class constructor is a special member function of a class that is executed whenever we create new objects of that class. 
- A constructor has exactly the same as that of class and it does not have any return type.

### What types of constructor availabe in c#?
- Default constructor.
- Parameterized constructor.
- Copy constructor.
- Static constructor.
- Private constructor.

### Different between Constructors and Method?
 | Constructor |Method|
 | ----------- | ---------- |
 | A consturctor is used to initialize an object | A method is used to expose the behavior of an object |
 | The constructor must not have a return type. | The method has or not have a return type. |
 | A constructor must be the same as the class name | Method name may or may not be same as the class name |
 | A constructor is invoked implicity. | A method is invoked explicity. |

### Default Construcor
`A constructor without any parameters is called a default constructor. If we do not create constructor the class will automatically call default constructor when an object is created.`
**Example :**
<pre class="prettyprint linenums:1"><ol class="linenums"><li class="L0"><code class="default prettyprint"><span class="kwd">public</span><span class="pln"> </span><span class="kwd">class</span><span class="pln"> </span><span class="typ">Person</span><span class="pln"></span><br></code></li><li class="L1"><code class="default prettyprint"><span class="pln"></span><span class="pun">{</span><span class="pln"></span><br></code></li><li class="L2"><code class="default prettyprint"><span class="pln"></span><span class="pun">}</span><span class="pln"> </span><br></code></li><li class="L3"><code class="default prettyprint"><span class="pln"></span><span class="kwd">public</span><span class="pln"> </span><span class="kwd">class</span><span class="pln"> </span><span class="typ">Person</span><span class="pln"></span><br></code></li><li class="L4"><code class="default prettyprint"><span class="pln"></span><span class="pun">{</span><span class="pln"></span><br></code></li><li class="L5"><code class="default prettyprint"><span class="pln">&nbsp; &nbsp; </span><span class="kwd">public</span><span class="pln"> </span><span class="typ">Person</span><span class="pun">()</span><span class="pln"> </span><span class="com">// Default constructor added by user</span><span class="pln"></span><br></code></li><li class="L6"><code class="default prettyprint"><span class="pln">&nbsp; &nbsp; </span><span class="pun">{</span><span class="pln"></span><br></code></li><li class="L7"><code class="default prettyprint"><span class="pln">&nbsp; &nbsp; &nbsp; &nbsp; </span><span class="com">// any code you can add here</span><span class="pln"></span><br></code></li><li class="L8"><code class="default prettyprint"><span class="pln">&nbsp; &nbsp; </span><span class="pun">}</span><span class="pln"></span><br></code></li><li class="L9"><code class="default prettyprint"><span class="pln"></span><span class="pun">}</span><span class="pln"> </span><br></code></li><li class="L0"><code class="default prettyprint"><span class="pln"></span></code></li></ol></pre>

### Parameterized Constructor

`A constructor having one or more parameters is called a parameterized constructor. If a class or struct have only parameterized constructor, to create an object of class/struct we need to pass all the parameters, otherwise we will get compilation error, let's see it with example:`