<!DOCTYPE HTML PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>C Sharp Learning Kit - Basic Content</title>
    <!-- Global CSS -->
    <link rel="Stylesheet" type="text/css" media="all" href="../Style/master.css" />
    <link rel="Stylesheet" type="text/css" media="all" href="../Style/Menu.css" />
    <link rel="Stylesheet" type="text/css" media="all" href="../Style/topnav.css" />
    <link rel="Stylesheet" type="text/css" media="all" href="../Style/body.css" />
    <link rel="Stylesheet" type="text/css" media="all" href="../Style/tier2-page.css" />
    <link rel="Stylesheet" type="text/css" media="all" href="../Style/sticky-footer.css" />
    <link rel="Stylesheet" type="text/css" media="all" href="../Style/campaign.master.css" />
    <link rel="stylesheet" type="text/css" href="../Style/style1.css" />
  


    <style type="text/css">
        .ctl00_TopNavMenu_0 {
            background-color: white;
            visibility: hidden;
            display: none;
            position: absolute;
            left: 0px;
            top: 0px;
        }

        .ctl00_TopNavMenu_1 {
            text-decoration: none;
        }

        .ctl00_TopNavMenu_2 {
        }

        .horimenu ul {
            list-style: none;
        }

        .horimenu li {
            display: inline;
            padding: .2em 1em;
        }
    </style>
</head>
<body>
    <a name="top"></a>
    <div id="outerWrapper">
        <div id="wrapper" class="landingPage getStartedPage">
            <div id="whiteBkgdStrip">
            </div>
            <div class="header">
                <div class="mainHomepageTitle">

                </div>



                <div class="mainHomepageSubTitle" style="font-size:18px">
                    Learning Kit
                </div>
                <div class="AspNet-Menu-Horizontal" id="ctl00_TopNavMenu">

                </div>
            </div>
            <div class="contentWrapper">
                <div class="twoColWrapper_80_20">
                   
                        <h1>Basic C Sharp Programming</h1>



                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="Framework"></a>
                        <h2>.NET Framework</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="IntroFramework"></a><strong>Introduction to .NET Framework</strong><br />
                               <br />
                                <p>
                                    <img src="Images/Framework_1.jpg"/><br /><br />
                                    .NET is a set of Microsoft software technologies and a computing platform. It simplifies application development in the highly distributed environment of Internet .NET platform is a computing platform layer that is positioned above the Windows operating system. The .NET Framework consists of the common language runtime and the .NET Framework class library.<br />
                                    You can think of the runtime as an agent that manages code at execution time, providing core services such as memory management and thread management, while also enforcing strict type safety and other forms of code accuracy that promote security and robustness.<br />
                                    The .NET Framework class library is a collection of reusable types that tightly integrate with the common language runtime. The class library is object-oriented, providing types from which your own managed code can derive functionality. This not only makes the .NET Framework types easy to use, but also reduces the time associated with learning new features of the .NET Framework.<br />
                                    The class library can be used to develop applications ranging from traditional command-line or graphical user interface (GUI) applications to applications based on the latest innovations provided by ASP.NET, such as Web Forms and XML Web services.<br />
                                    .NET Framework makes it possible to write applications in one of the .NET supported language and using functionality of the vast collection of .NET class libraries. The applications can be executed on computer running .NET Framework.
                                    <br /><br />
                                    The Common Language Runtime (CLR) performs some vital functionality:<br />
                                    <ul>
                                        <li>Automatic Memory Management</li>
                                        <li>Provides garbage collection</li>
                                        <li>Exception Handling</li>
                                        <li>Language Interoperability (which includes COM Interop)</li>
                                        <li>Platform Independence</li>
                                    </ul>
                                    <br />
                                    CLS is a set of basic language guidelines that specify the features needed by .NET applications to fully interact with other objects regardless of their implementation language. It has been created to improve language interoperability. The Framework Class Libraries are CLS compliant.
                                    <br /> Some examples of CLS guidelines are:
                                    <ul>
                                        <li>Cannot overload based on return type</li>
                                        <li>Unsigned integer types are not allowed on public methods</li>
                                        <li>Array index has to start from 0</li>
                                    </ul>
                                    The CLR defines the Common Type System (CTS). All .NET languages map into the CTS. CLR types are defined under the System namespace. All .NET languages provide their own keywords that map to the underlying CTS types e.g.
                                    <ul>
                                        <li>C# int keyword = System.Int32</li>
                                        <li>VB.NET integer keyword = System.Int32</li>
                                    </ul>
                                    <br />
                                    For more, please refer: http://msdn.microsoft.com/en-us/library/zw4w595w(v=vs.90).aspx
                                </p>

                            </li>
                            <li>
                                <a name="ExecutionModel"></a><strong>.NET Framework Execution Model</strong><br />
                               <br />
                                <p>
                                    <img src="Images/ExecutionModel_1.jpg" /><br /><br />
                                    The code written in one of the .NET languages would be compiled into Intermediate Language using the language specific compiler. This results into an assembly, usually EXE or DLL, which can be executed on any machine with .NET Framework. The code can refer to the .NET Class Libraries. The code can also refer to any other assembly, originally written in same or any other .NET Language.<br />
                                    The assembly is executed by the Just in Time compiler of the Common Language Runtime. It can invoke other class libraries at the time of invocation. The JIT compiler converts the IL code to machine’s native code, which can be directly read by the operating system.<br />

                                </p>

                            </li>
                            <li>
                                <a name="3.5Architecture"></a><strong>.NET 3.5 Architecture</strong><br />
                               <br />
                                <p>
                                    .NET 3.5 Framework is built upon on CLR 2.0 + Service Pack 1. It contains all class libraries of .NET Framework 3.0 with four major enhancements- LINQ, Entity Framework, ASP.Net Dynamic Data and AJAX. .NET Framework 3.0 in itself is same as .NET 2.0 with four major enhancements- WPF, WCF, Workflows and Cardspace.
                                    <br />
                                    <br />
                                    <img src="Images/3.5Framework.jpg" />
                                    <br />
                                    For more information, please refer: http://msdn.microsoft.com/en-us/library/bb822049(v=vs.90).aspx
                                </p>

                            </li>
                            <li>
                                <a name="4.0Framework"></a><strong>.NET 4.0 Architecture</strong><br />
                                <br />
                                <p>
                                    
                                    <br />
                                    <img src="Images/4.0Framework_1.jpg" /><br /><br />
                                    .NET 4.0 Framework is built upon CLR 4.0 and introduces a completely standalone technology that does not require other previous versions to be installed. Following are the new features introduced in .NET 4.0.
                                    <ul>
                                        <li>
                                            Managed Extensibility Framework (MEF):<br />
                                            The Managed Extensibility Framework or MEF is a library for creating lightweight, extensible applications.<br />
                                            Assume that while designing a large enterprise application, developer needs to include a potentially large number of smaller components. The simplest approach to the problem is to include the components as source code in application, however it has obvious drawbacks like modifying the source code, tight coupling etc. Instead of this explicit registration of available components, MEF provides a way to discover them implicitly with no configuration required. It allows extensions to be reused from application to application.<br />

                                        </li>
                                        <li>
                                            Parallel Computing:<br />
                                            To enhance the performance, the Task parallel library (TPL), Parallel class, Parallel LINQ etc. are introduced in .NET 4.0. When the methods in parallel class are used, the.NET runtime automatically manages the parallel execution of tasks through multithreading.
                                        </li>
                                        <li>
                                            Dynamic Language Runtime:<br />
                                            The dynamic language runtime (DLR) is a new runtime environment that makes it easier to run the dynamic languages (ruby, python etc.) on the .NET Framework and to add dynamic features to statically typed languages. To support the DLR, the new System.Dynamic namespace is added to the .NET Framework.
                                        </li>
                                        <li>
                                            Portable class libraries:<br />
                                            Portable class libraries introduced in .NET 4.0 can run on a variety of .NET Framework platforms such as Silverlight, Windows Phone 7, or Xbox 360 platforms without recompiling.
                                        </li>
                                        <li>
                                            Others :<br />
                                            <ul>
                                                <li><b>Lazy Initialization:</b>Objects are not allocated memory until it is needed.  </li>
                                                <li><b>In Process Side by Side Execution: </b>This feature enables an application to load and start multiple versions of the .NET Framework in the same process.</li>
                                                <li><b>Client Profile : </b>This feature enables an application to load and start multiple versions of the .NET Framework in the same process.</li>
                                                <li><b>Application Compatibility: </b>The .NET Framework 4 is highly compatible with applications that are built with earlier .NET Framework versions. If required, the applications can be made to run with a particular framework by setting in Project Properties.</li>
                                            </ul>
                                        </li>
                                        <li>
                                            Language Enhancements<br />
                                            <ul>
                                                <li><b>Named and Optional Parameters: </b>Named parameters enables to specify an argument for a particular parameter by associating the argument with the parameter's name. Optional parameters allow to omit arguments to some parameters.</li>
                                                <li><b>ExpandoObject class: </b>Represents an object whose members can be dynamically added and removed at run time</li>
                                                <li><b>Code Contracts: </b>Code contracts provide a way to specify preconditions, post conditions, and object invariants in code</li>
                                            </ul>
                                        </li>
                                    </ul>
                                    For more on .NET Framework 4.0, please refer: https://msdn.microsoft.com/en-us/library/vstudio/ms171868(v=vs.100).aspx
                                </p>

                            </li>
                            <li>
                                <a name="4.5Framework"></a><strong>.NET 4.5 Architecture</strong><br />
                                
                                <br />
                                <p>
                                    <img src="Images/4.5Framework_1.jpg" /><br /><br />
                                    Following new features were added to the .NET 4.5 Framework:
                                    <ul style="list-style-type:decimal">
                                        <li>
                                            <b>Background garbage collection: </b>
                                            .NET 4.5 achieves better performance through background garbage collection for servers. When the server garbage collection is used in the .NET Framework 4.5, background garbage collection is automatically enabled
                                        </li>
                                        <li>
                                            <b>Profile Optimization: </b>
                                            .NET 4.5 adds a new feature called as Background just-in-time (JIT) compilation, which is optionally available on multi-core processors to improve application performance.
                                        </li>
                                        <li>
                                            <b>Regex Time out: </b>
                                            This feature defines the ability to limit how long the regular expression engine will attempt to resolve a regular expression before it times out
                                        </li>
                                        <li><b>UTF console support: </b>Console support for Unicode (UTF-16) encoding</li>
                                        <li><b>Zip compression:</b>Zip compression improvements to reduce the size of a compressed file. It is available under System.IO.Compression namespace</li>
                                        <li><b>2 GB array support: </b>Support for arrays that are larger than 2 gigabytes (GB) on 64-bit platforms. This feature can be enabled in the application configuration file</li>
                                        <li><b>Asynchronous File operations: </b>In the .NET Framework 4.5, new asynchronous features were added to the C# and Visual Basic languages. These features add a task-based model for performing asynchronous operations</li>
                                        <li><b>Tools: </b>The Resource File Generator tool converts text (.txt or .restext) files and XML-based resource format (.resx) files to common language runtime binary. Managed Profile Guided Optimization (Mpgo.exe) tool enables to improve application startup time, memory utilization (working set size), and throughput by optimizing native image assemblies</li>
                                    </ul>
                                </p>

                            </li>
                          
                            <li>
                                <a name="CompFramework"></a><strong>Comparison between .NET Frameworks</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="../Quiz/Framework.htm">Quiz</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                </ul>
                                <br />
                            <p>
                                <img src="Images/4.0Framework.jpg" />
                            </p>

                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>

                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="VS2013"></a>
                        <h2>Visual Studio 2013</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="OverviewVS2013"></a><strong>Overview of Visual Studio 2013</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="../Demos/BasicCSharp.htm#VS2013">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                </ul>
                                <p>
                                    Visual Studio is a complete set of development tools for .NET Applications. Visual Studio is optimized for team-based design, development, and deployment of enterprise solutions.


                                    <ul>
                                        <li>Tool for writing, compiling, executing and deploying .NET Projects</li>
                                        <li>In-built templates for creating a new project</li>
                                        <li>Manage solutions, projects and files</li>
                                        <li>In-built support for testing, debugging and code analysis</li>
                                        <li>Deploying applications</li>
                                    </ul>
                                    Visual Studio provides a number of in built templates which help in creation of the desired type of application.<br />
                                    The file editor can be used to edit a program or resource file.<br />
                                    Please refer to the corresponding solved assignment in the lab guide.<br />
                                    For more, please refer: http://msdn.microsoft.com/en-us/library/bb822049(v=vs.90).aspx

                                </p>

                            </li>


                        </ul>
                        <p><a href="#top">Top of page</a></p>

                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="ProgrammingBasics"></a>
                        <h2>C# Programming Basics</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="CSharpStructure"></a><strong>Structure of C# Program</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/1/1" target="_blank">Video</a></li>
                                    <li class="last"><a href="../Demos/BasicCSharp.htm#CSharpStructure">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                </ul>
                                <p>
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
class ClassName 
{
    DataType1 MemberVariable1; 
    ClassType2 object2; 
    /* A data member can be defined using 
    	 1) primitive types (int, float, string …)
		 2) user defined structures
		 3) object reference of a class */  
    ClassName( parameters ) 
    {
    /*	The constructor is used for members initialization
       during the object creation */
	}
    return-type MethodName( parameters ) 
    {   
    /* All the application logics have to be placed 
		inside the methods. A method must be placed inside a
       class.*/ 	 
    }
}// End of the class
</pre>
                                        </div>
                                    </div>
                                </p>

                            </li>
                            <li>
                                <a name="ClassAndObject"></a><strong>Class and Object</strong><br />
                                <ul class="horimenu anchorLinks">

                                    <li class="last"><a href="http://digitaltutor/#/video/6/1/0" target="_blank">Video</a></li>
                                    
                                
                                </ul>
                                <p>
                                    A Class is a blue print used to create objects. It is a software template that defines the methods and variables to be included in a particular kind of Object.<br />
                                    A class contains state and behavior. State (Data Members) is a set of variables defined inside the class. Behavior (Member Methods) is a set of functions defined inside the class.<br />
                                    An object is a unique, identifiable, self-contained entity that contains attributes and behaviors. An object is an instance of a class.<br />
                                    <br />
                                    <div class="codesnippet">
public class Category<br />
{<br />
    short categoryId;  <br />
    string categoryName;<br />
<br />
public short GetCetegoryId()<br />
{<br />
    return categoryId;<br />
}<br />
<br />
public void SetCategoryId(short categoryId)<br />
{<br />
    this.categoryId = categoryId;<br />
}<br />
}<br />
                                    </div>
                                    <br />
                                    The terms class and object are sometimes used interchangeably, but in fact, classes describe the type of objects, while objects are usable instances of classes. So, the act of creating an object is called instantiation. Using the blueprint analogy, a class is a blueprint, and an object is a building made from that blueprint.<br />
                                    The keyword &quot;public&quot; implies the accessibility of the code element from anywhere in the application. <br />
                                    The keyword &quot;this&quot; implies that the current objects member would be used. This would be useful in resolving conflict between names of data members and method variables or parameters.<br />
                                </p>

                            </li>
                            <li>
                                <a name="DataTypes"></a><strong>Data Types</strong><br />
                                <ul class="horimenu anchorLinks">

                                    <li class="last"><a href="http://digitaltutor/#/video/6/3/0" target="_blank">Video</a></li>
                                </ul>
                                <p>
                                    <img src="Images/DataTypes_1.jpg" /><br />
                                    C# is a strongly-typed language. Before a value can be stored in a variable, the type of the variable must be specified, as in the following examples:<br />
                                    <br /><br />
                                    <div class="codesnippet">
                                        int num = 1;<br />
                                        string greet = "Hello";<br />
                                        Customer customer = new Customer();<br />
                                    </div>
                                    <br /><br />
                                    Note that the type must be specified both for simple, built-in types such as an int, and for complex or custom types such as Customer.<br />
                                    <br />

                                    <br /><br />
                                    <table border='3 solid black' class="content-table">
                                        <tr>
                                            <strong>C# Type	.NET Framework Type	Range</strong>
                                            <br />
                                        </tr>
                                        <tr><td>bool</td>	<td>System.Boolean</td>	<td>True or False.</td></tr>
                                        <tr><td>byte</td>	<td>System.Byte</td>	<td>0... 255</td></tr>
                                        <tr><td>sbyte</td>	<td>System.SByte</td>	<td>-128... 127</td></tr>
                                        <tr><td>char</td>	<td>System.Char</td>	<td>A Unicode character.</td></tr>
                                        <tr><td>decimal</td>	<td>System.Decimal</td>	<td>-79228162514264337593543950335... 79228162514264337593543950335</td></tr>
                                        <tr><td>double</td>	<td>System.Double</td>	<td>-1.79769313486232e308... 1.79769313486232e308</td></tr>
                                        <tr><td>float</td>	<td>System.Single</td>	<td>-3.402823e38... 3.402823e38</td></tr>
                                        <tr><td>int</td>	<td>System.Int32</td>	<td>-2,147,483,648... 2,147,483,647</td></tr>
                                        <tr><td>uint</td>	<td>System.UInt32</td>	<td>0.. 4,294,967,295</td></tr>
                                        <tr><td>long</td>	<td>System.Int64</td>	<td>-9,223,372,036,854,775,808... 9,223,372,036,854,775,807</td></tr>
                                        <tr><td>ulong</td>	<td>System.UInt64</td>	<td>0.. 18,446,744,073,709,551,615</td></tr>
                                        <tr><td>object</td>	<td>System.Object</td>	<td>An object.</td></tr>
                                        <tr><td>short</td>	<td>System.Int16</td>	<td>-32,768... 32,767</td></tr>
                                        <tr><td>ushort</td>	<td>System.UInt16</td>	<td>0.. 65,535</td></tr>
                                        <tr><td>string</td>	<td>System.String</td>	<td>A string of Unicode characters.</td></tr>
                                    </table>
                                    <br /><br />
                                    These data type names are aliases for predefined types in the System namespace, as indicated. These types, with the exception of object and string, are value types. Values types and reference types are covered in the next section.<br /><br />

                                    If a numeric data type is assigned with a value outside its range, it oscillates to the other end of the range e.g. <br /><br />
                                    <div class="codesnippet">
int num = -2147483648;<br />
Console.Write(--num);  //Prints 2147483647<br />
<br /><br />

int num = 2147483647;<br />
Console.Write(++num);  //Prints -2147483648<br />
                                    </div>
                                    <br />
                                    Converting between data types can be done implicitly, in which the conversion is done automatically by the compiler, or explicitly using a cast, in which the programmer forces the conversion, and assumes the risk of losing information. For example:<br /><br />
                                    <br />
                                    <div class="codesnippet">
int i = 0;<br />
double d = 0;<br /><br /><br />

i = 10;<br />
d = i;        // An implicit conversion<br />
<br /><br />
d = 3.5;<br />
i = (int)d;  // An explicit conversion, or "cast"<br />
                                    </div>

                                    <br /><br />
                                    Conversions as above can be done only between compatible types.<br /><br />
                                </p>

                            </li>
                         
                            <li>
                                <a name="RefValueTypes"></a><strong>Reference and Value Types</strong><br />
                                <br />

                                <p>
                                    C# has two varieties of data types: value and reference. A value type stores its contents in memory allocated on the stack. For example, in this case the value 42 is stored in an area of memory called the stack:
                                    <br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
int x = 42;
</pre>
                                        </div>
                                    </div>
                                    When the variable x goes out of scope because the method in which it was defined has finished executing, the value is discarded from the stack. Using the stack is efficient, but the limited lifetime of value types makes them less suited for sharing data between different classes.
                                    <br /><br />
                                    In contrast, a reference type, such as an instance of a class or an array, is allocated in a different area of memory called the heap. In the example below, the space required for the ten integers that make up the array is allocated on the heap.
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
int[] numbers = new int[10];
</pre>
                                        </div>
                                    </div>
                                    This memory isn't returned to the heap when a method finishes; it's only reclaimed when C#'s garbage collection system determines it is no longer needed. There is a greater overhead in declaring reference types, but they have the advantage of being accessible from other classes.
                                   
                                </p>

                            </li>
                            <li>
                                <a name="NullableTypes"></a><strong>Nullable Types</strong><br /><br />
                            

                                <p>
                                    Nullable types are instances of the System.Nullable &lt;t&gt; <br />
                                        struct. A nullable type can represent the correct range of values for its underlying value type, plus an additional null value.<br />
                                        For example, a Nullable&lt;Int32&gt; <br />
                                            , pronounced "Nullable of Int32," can be assigned any value from -2147483648 to 2147483647, or it can be assigned the null value. A Nullable &lt;bool&gt;
                                                can be assigned the values true false, or null.<br />
                                                The ability to assign null to numeric and Boolean types is especially useful when you are dealing with databases and other data types that contain elements that may not be assigned a value. For example, a Boolean field in a database can store the values true or false, or it may be undefined.
                                    <br /><br />
                                                Any value type may be used as the basis for a nullable type. For example:<br />


                                        <div class="codesnippet">
                                            <div>
                                                <pre>
int? i = 10;
double? d1 = 3.14;
bool? flag = null;
char? letter = 'a';
int?[] arr = new int?[10];

</pre>
                                            </div>
                                        </div>
                                    <br />
                                    Each instance of a nullable type has two public read-only properties:<br />
                                    <ul>
                                        <li><b>HasValue</b><br />
                                            HasValue is of type bool. It is set to true when the variable contains a non-null value</li>
                                        <li><b>Value</b><br />Value is of the same type as the underlying type. If HasValue is true, Value contains a meaningful value. If HasValue is false, accessing Value will throw a InvalidOperationException<br />
                                        <br />
                                        <div class="codesnippet">
                                            <div>
                                                <pre>
int? x = 10;
if (x.HasValue)
{
    Console.WriteLine(x.Value);
}
else
{
    Console.WriteLine("Undefined");
}

</pre>
                                            </div>
                                        </div>
                                        
                                        </li>
                                    </ul>
                                    <br />

                                    Nullable types have the following characteristics:
                                    <br />
                                    <ul>
                                        <li>	Nullable types represent value-type variables that can be assigned the value of null. You cannot create a nullable type based on a reference type. (Reference types already support the null value.)
                                        </li>
                                        <li>The syntax T? is shorthand for Nullable&lt;T&gt;, where T is a value type. The two forms are interchangeable.
                                            </li>
                                        <li>Assign a value to a nullable type just as you would for an ordinary value type, for example int? x = 10; or double? d = 4.108. A nullable type can also be assigned the value null: int? x = null
                                        </li>
                                        <li>Use the Nullable&lt;T&gt;.GetValueOrDefault method to return either the assigned value, or the default value for the underlying type if the value is null, for example int j = x.GetValueOrDefault();
                                            </li>
                                        <li>Use the HasValue and Value read-only properties to test for null and retrieve the value, as shown in the following example: if(x.HasValue) j = x.Value;
                                        <ul>
                                            <li>The HasValue property returns true if the variable contains a value, or false if it is null</li>
                                            <li>The Value property returns a value if one is assigned. Otherwise, a System.InvalidOperationException is thrown</li>
                                            <li>The default value for HasValue is false. The Value property has no default value</li>
                                            <li>You can also use the == and != operators with a nullable type, as shown in the following example: if (x != null) y = x;</li>
                                        </ul>
                                        </li>
                                        <li>Use the ?? operator to assign a default value that will be applied when a nullable type whose current value is null is assigned to a non-nullable type, for example int? x = null; int y = x ?? -1;
                                        </li>
                                        <li>Nested nullable types are not allowed. The following line will not compile: Nullable&lt;Nullable&lt;Int&gt;&gt; n;
                                        </li>
                                    </ul>


                                </p>

                            </li>

                            <li>
                                <a name="ClassLib"></a><strong>Class Library</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="../Demos/BasicCSharp.htm#ClassLib">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    <li class="last"><a href="../Quiz/Basic.htm">Quiz</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                </ul>
                                <p><ul><li>Reusable component of code</li><li>Cannot execute on its own</li></ul></p>

                            </li>
                            <li>
                                <a name="Method"></a><strong>Methods</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="../Demos/BasicCSharp.htm#Method">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                </ul>
                                <p>
                                    <ul>
                                        <li>A code block containing a set of statements</li>
                                        <li>Main() method is the entry point for every C# application execution</li>
                                        <li>Methods are declared in a class or struct by specifying the access level such as public or private</li>
                                        <li>Method parameters are enclosed in paratheses and are separated by commas</li>
                                        <li>Empty parantheses indicate that the method requires no parameters</li>
                                        <li>A return-type of a method is not part of the signature of the method</li>
                                        <br />
                                        <br />
                                        access-specifier return-type MethodName(parameter1, parameter2, ...)
                                        <br />
                                        {
                                        <br />
                                        &nbsp;&nbsp;	&nbsp;	&nbsp;	/*The application logic has to be placed inside a method.
                                        <br />
                                        &nbsp;&nbsp;	&nbsp;	&nbsp;  A method must be placed inside a class.*/
                                        <br />
                                        }
                                        <br />
                                    </ul>
                                    <br /><br />
                                    The variables and objects that are declared inside a method are local variables and local objects.<br />
                                    The parameters passed to a method are also treated as local to that particular method<br />
                                    The local variables and local objects can be accessed only within the method in which they are declared<br />
                                    By default, all the variables are passed by value to the methods<br />
                                    By default, all the objects are passed by reference to the methods<br />
                                    The default behaviors of passing the parameters can be changed. This will be discussed soon.
                                    <br />
                                </p>

                            </li>
                            <li>
                                <a name="Constructors"></a><strong>Constructors</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/3/1">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    <li class="last"><a href="../Demos/BasicCSharp.htm#Constructor">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                </ul>
                                <p>
                                    Constructors are special methods in a class which get executed at the time of creation of object. A constructor is different from other methods in two ways:<br />
                                    <ul>
                                        <li>
                                            A constructor is identified by its name, which is the same as the name of class

                                        </li>
                                        <li>
                                            A constructor does not have any return type (even void should not be mentioned)

                                        </li>
                                    </ul>
                                    A class can have any number of overloaded constructors. Depending on the parameters passed at the time of instantiating the class, a suitable overload is called. This is similar to calling overloaded methods.<br />
                                    In case, no constructor is written by the programmer, a default constructor, with no parameters, is supplied by the compiler. This ensures that the programmer need not write a constructor if no specific code needs to be executed at the time of object creation
                                    <br />To exit from the constructor, return; can be used

                                    <div class="codesnippet">
                                        <div>
                                            <pre>
public class Category
{
    short categoryId;
    string categoryName;
}
class Program
{
    static void Main(string[] args)
    {
        Category category = new Category();//Default Constructor is called
    }
}
</pre>
                                        </div>
                                    </div>

                                </p>

                            </li>

                        </ul>
                        <p><a href="#top">Top of page</a></p>

                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="StaticPoly"></a>
                        <h2>Static Polymorphism</h2>
                        <ul class="getStartedList">
                          
                            <li>
                                <a name="MethodOverloading"></a><strong>Method Overloading</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/7/3" target="_blank">Video</a></li>
                                    <li class="last"><a href="../Demos/BasicCSharp.htm#MethodOverloading">Demo</a></li>
                                    <li class="last"><a href="../Assignments/BasicCSharp.htm#Day1_1">Assignment</a></li>
                                   

                                </ul>
                                <p>
                                    More than one method within the same class having same name but with different signatures are termed as overloaded methods. The compiler will treat each of these methods as different method.<br />
                                    <br />
                                    Calls to overloaded methods will be resolved during compile time. Hence, it is categorized as static polymorphism<br />
                                    <br />
                                    Signature of the method could differ in one or more of following ways, for it to be overloaded in C#:<br />
                                    <ul>
                                        <li>	Number of parameters</li>
                                        <li>
                                            Data type of parameters
                                        </li>
                                        <li>
                                            Sequence of parameters of different data-types
                                        </li>
                                    </ul>
                                    <br />
                                    If difference is only in terms of return type, the compiler does not accept the methods as overloaded, and gives an error.<br />
                                    <br />
                                    When a method is called, all its overloads are checked and following action is taken:<br />
                                    <br />
                                    <ol type="1">
                                        <li>	If none of the overloads matches with the method call, an error is thrown.</li>
                                        <li>If exactly one overload matches with the method call, that overload is called.</li>
                                        <li>
                                            If more than one overloads match the method call, the various overloads are compared to determine the best match:
                                            <ol type="a">
                                                <li> If only one overload is determined to be the best match for the method call, that overload is called.</li>
                                                <li>
                                                    If it is not possible to determine a single overload as the best match for the method call, an error is thrown.
                                                </li>
                                            </ol>
                                        </li>
                                    </ol>
                                    <br />
                                    To understand the above let us consider following classes with overloaded methods and calls:
                                    <br /><br />
                                </p>
                                <p>
                                    <div class="codesnippet">
class Program<br />
{<br />
&nbsp;&nbsp;&nbsp;&nbsp; static void Main(string[] args)<br />
&nbsp;&nbsp;&nbsp;&nbsp;{<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MathApp mathApp = new MathApp();<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mathApp.Add(1.0f, 1.0f);<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mathApp.Add(1.0f);<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mathApp.Add(1);<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mathApp.Add(1,1);<br />
&nbsp;&nbsp;&nbsp;&nbsp;}<br />
}<br />
class MathApp<br />
{<br />
&nbsp;&nbsp;&nbsp;&nbsp;public int Add(int num)<br />
&nbsp;&nbsp;&nbsp;&nbsp;{<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return num + 10;<br />
&nbsp;&nbsp;&nbsp;&nbsp;}<br />
&nbsp;&nbsp;&nbsp;&nbsp;public float Add(float num)<br />
&nbsp;&nbsp;&nbsp;&nbsp;{<br />
&nbsp;&nbsp;&nbsp;&nbsp;return num + 10;<br />
&nbsp;&nbsp;&nbsp;&nbsp;}<br />
&nbsp;&nbsp;&nbsp;&nbsp;public float Add(int num1, float num2)<br />
&nbsp;&nbsp;&nbsp;&nbsp;{<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return num1 + num2;<br />
&nbsp;&nbsp;&nbsp;&nbsp;}<br />
&nbsp;&nbsp;&nbsp;&nbsp;public float Add(float num1, int num2)<br />
&nbsp;&nbsp;&nbsp;&nbsp;{<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return num1 + num2;<br />
&nbsp;&nbsp;&nbsp;&nbsp;}<br />
}
                                        <br />
                                    </div>
                                </p>

                                An overload is considered to be matching a method call if both have the same number and type of parameters, with or without an implicit conversion.<br />
                                <br />
                                The following matrix gives the matching between overloads and method calls for the above example:<br />
                                <br />
                                <table border="1px solid black" cellpadding="0" cellspacing="0" class="content-table">

                                    <tr>
                                        <th rowspan="6"><span style="-moz-transform: rotate(-90.0deg);-o-transform: rotate(-90.0deg);-webkit-transform: rotate(-90.0deg);"> Method Overloads</span></th>
                                        <th colspan="5">
                                            Method Calls
                                        </th>
                                    </tr>
                                    <tr><th></th><th>Add(1.0f, 1.0f)</th>	<th>Add(1.0f)</th>	<th>Add(1)</th>	<th>Add(1,1)</th></tr>
                                    <tr>
                                        <th>Add(int)</th>
                                        <td>N</td>
                                        <td>N</td>
                                        <td>Y</td>
                                        <td>N</td>
                                    </tr>
                                    <tr>
                                        <th> Add(float)</th>
                                        <td>N</td>
                                        <td>Y</td>
                                        <td>Y</td>
                                        <td>N</td>
                                    </tr>
                                    <tr>
                                        <th>Add(int, float)</th>
                                        <td>N</td>
                                        <td>N</td>
                                        <td>N</td>
                                        <td>Y</td>
                                    </tr>
                                    <tr>
                                        <th>Add(float, int)</th>
                                        <td>N</td>
                                        <td>N</td>
                                        <td>N</td>
                                        <td>Y</td>
                                    </tr>
                                </table>
                                <br />
                                <ol typeof="1">
                                    <li>As evident, no overloads match Add(1.0f, 1.0f), and, hence, it cannot be executed. Error is thrown on this call.</li>
                                    <li>
                                        For Add(1.0f), there is only one matching overload. Hence, that will be executed.
                                    </li>
                                    <li>
                                        For Add(1) and Add(1,1), there are 2 matching overloads each, hence, we need to assess the best match:
                                        <ol type="a">
                                            <li>	For Add(1), Add(int) is needs no implicit typecast, but Add(float) needs implicit type cast. Hence, Add(int) can be considered as best match, and executed.</li>
                                            <li>	For Add(1,1), both Add(int, float) and Add(float, int) need implicit type cast int to float of 1 parameter only.  Both are equally good matches, and we cannot declare one as best match. This will hence throw an error.</li>
                                        </ol>
                                    </li>
                                </ol>


                            </li>
                            <li>
                                <a name="ConstructorOverloading"></a><strong>Constructor Overloading</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/7/3" target="_blank">Video</a></li>
                                    <li class="last"><a href="../Demos/BasicCSharp.htm#ConstructorOverloading">Demo</a></li>

                                    <li class="last"><a href="../Quiz/Overloading.htm">Quiz</a></li>&nbsp;&nbsp;&nbsp;&nbsp;


                                </ul>
                                <p>
                                    If the programmer writes one or more constructor, with or without parameters, the compiler does not provide the default constructor. This is to ensure that the object is created only in those ways that the programmer wants.

                                    <div class="codesnippet">
                                        <div>
                                            <pre>
public class Category
{
    short categoryId;
    string categoryName;
    public Category(short categoryId)
    {
        this.categoryId = categoryId; //“this” points to member of the object
    }
    public Category(short categoryId, string categoryName)
    {
        this.categoryId = categoryId;
        this.categoryName = categoryName;
    }
}
class Program
{
    static void Main(string[] args)
    {
        Category category1 = new Category(); //Invalid
        Category category2 = new Category(101); //Valid
        Category category3 = new Category(101, "Electronics"); //Valid
    }
}
</pre>
                                        </div>
                                    </div><br />
                                    It is good practice to avoid redundant code in overloaded constructors. Constructors can be called from each other, if needed.
                                    <br /><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
public class Category
{
    short categoryId;
    string categoryName;
    public Category(short categoryId)
    {
        this.categoryId = categoryId;
    }
    public Category(short categoryId, string categoryName): this(categoryId)
	//Constructor is called using “this()”
    {           
        this.categoryName = categoryName;
    }
}
</pre>
                                        </div>
                                    </div><br /><br />
                                    this() can be used to call constructor of the same class as shown above. Parameters can be passed depending on the constructor overload to be called

                                </p>

                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>


                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="Arrays"></a>
                        <h2>Arrays</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="ArraysIntro"></a><strong>Arrays</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/10/0">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    <li class="last"><a href="../Demos/BasicCSharp.htm#Array">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                </ul>
                                <p>
                                    You can store multiple variables of the same type in an array data structure. You declare an array by specifying the type of its elements.<br />
                                    The number of dimensions and the length of each dimension are established when the array instance is created. These values can't be changed during the lifetime of the instance.<br />
                                    <br />
                                     The default values of numeric array elements are set to zero, and reference elements are set to null.<br />
                                    Arrays are zero indexed: an array with n elements is indexed from 0 to n-1.<br />
                                    Array types are reference types derived from the abstract base type Array.<br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
int[] intArr = new int[10];
int[] intArr2 = { 3, 6, 9, 1, 2 };
Category[] categoryArr = new Category[4];
Category[] categoryArr2 = { new Category(1, "Electronics"), new Category(2, "Home Appliances") };
</pre>
                                        </div>
                                    </div>
                                    <br />
                                    Arrays have a property “Length” which can be used to get the size of array.<br /><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
Category[] categoryArr = new Category[4];
for (int index = 0; index < categoryArr.Length; index++)
{
    //Perform operation on each element of array
}
</pre>
                                        </div>
                                    </div>
                                </p>

                            </li>
                            <li>
                                <a name="Foreach"></a><strong>foreach</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="../Demos/BasicCSharp.htm#Foreach">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                </ul>
                                <p>
                                    So far, we have used a “for” loop to enumerate through the elements of an array. In order to do so, we need to provide a logic for moving from one element to another e.g. by incrementing the index.
                                    <br /><br />
                                    This is possible only if there is an access mechanism which follows a pattern (e.g. index)
                                    <br />
                                    foreach can be used to enumerate through an array or collection, without the need of such an access mechanism, and in an easier manner.<br />
                                    <br />Syntax –<br /><br />
                                    foreach ( type identifier in expression)<br />
                                    {<br />
                                    //statements<br />
                                    }<br /><br />
                                    Where<br />
                                    type – type of identifier<br />
                                    identifier – either an array element or a collection element<br />
                                    expression – an array or a collection, whose elements are fetched in iteration<br />

                                    <div class="codesnippet">
                                        <div>
                                            <pre>
public class Program
{
    public static void Main()
    {
        int[] arrNum = { 10, 20, 30, 40 };
        foreach (int number in arrNum)
        {
            Console.WriteLine(number);
        }
    }
}
</pre>
                                        </div>
                                    </div>
                                </p>

                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>


                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <!--<a name="Static"></a>
                        <h2>'static' keyword</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="Method"></a><strong>Static Members, Constructor and Classes</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/3/3">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    <li class="last"><a href="../Demos/BasicCSharp.htm#Static">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                    <li class="last"><a href="../Exercises/BasicCSharp.htm#Day1_1">Exercise</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                    <li class="last"><a href="../Assignments/BasicCSharp.htm#Day1_2">Assignment</a></li>&nbsp;&nbsp;&nbsp;&nbsp;          

                                </ul>
                                <p>
                                    The “static” keyword can be used for data members, methods, constructors and classes.<br />
                                    <br />
                                    A static data member is a variable which belongs to the class. A single copy of static data member is shared by all instances of the class. Any modification in value of static data member from one instance will be visible to others.
                                    <br /><br />
                                    For the use of static variables, creation of instance is not required. Accessed using &lt;class-name&gt;.&lt;variable-name&gt; unlike instance variables which are accessed as &lt;object-name&gt;.&lt;variable-name&gt;.
                                    <br /><br />
                                  
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
public class Category
{
    static short categoryCount = 101;
    short categoryId;
    string categoryName;
    public Category()
    {
        this.categoryId = categoryCount++;
    }
    public Category(string categoryName): this()
    {           
        this.categoryName = categoryName;
    }
}
class Program
{
    static void Main(string[] args)
    {
        Category category1 = new Category(); 
        Category category2 = new Category("Electronics");
    }
}
</pre>
                                        </div>
                                    </div>
                                    <p>
                                    <img  src="Images/Static_1.jpg" /><br />
                                        </p>
                                    Like any static data member, static method belongs to the class (and not to the objects created for the class).  So, it is a class level method. It is accessed using “class_name.method_name”. For using static methods, creation of instance is not necessary.
                                    <br /><br /><br />
                                    A static method can only access other static data members and static methods. Static methods cannot access instance data members and instance member methods. However, non-static methods can access static data members and static methods.
                                <br /><br />    
                                <div class="codesnippet">
                                        <div>
                                            <pre>
public class Category
{
    static short categoryCount = 101;
    short categoryId;
    string categoryName;
    public Category()
    {
        this.categoryId = categoryCount++;
    }
    public Category(string categoryName): this()
    {           
        this.categoryName = categoryName;
    }
    public static void PrintNumberOfCategories()
    {
        Console.WriteLine("Number of Categories = " + categoryCount);
    }
    public void PrintCategoryDetails()
    {
        Console.WriteLine("Category Id = " + categoryId);
        Console.WriteLine("Category Name = " + categoryName);
        PrintNumberOfCategories();
    }
}
</pre>
                                        </div>
                                    </div>
                                <br />
                                <br />
                                    Static constructor can be used to perform some action at the very first time a class is loaded. Static constructor for one class is invoked utmost once in the lifetime of the application. It is invoked automatically and cannot be invoked explicitly. <br />
                                    The events which can lead to invocation of a static constructor are as follows:<br />
                                    <ul>
                                        <li>A static method of the class is invoked</li>
                                        <li>A static data member of the class is referred</li>
                                        <li>An object of the class is created</li>
                                    </ul>
                                    Creation of a class reference cannot lead to invocation of static constructor.
                                    <br />
                                    A class can have only one static constructor. Similar to non-static constructors, static constructors also have the same name as the class. Static constructor cannot have any parameter. Static constructor cannot have any access specifiers. It can be used to initialize the static data members of the class.
                                    <br /><br />
                                    Static Constructors are suitable for those member initializations which need to be done based on some code e.g. if you need to initialize a static data member to a value to be read from a file or database, it can be conveniently done using static constructor.
                                    <br /><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
public class Category
{
    static short categoryCount;
    short categoryId;
    string categoryName;
    static Category()
    {
        //Fetch a value from database and initialize categoryCount
    }
    public Category()
    {
        this.categoryId = categoryCount++;
    }
    public Category(string categoryName): this()
    {           
        this.categoryName = categoryName;
    }
}
</pre>
                                        </div>
                                    </div><br /><br />
                                    In case of inheritance (to be covered later), the static constructor invocation starts from child. This means first the child class static constructor is called followed by parent class.
                                    <br /><br />
                                    A static class is a class that cannot be instantiated. As it cannot be instantiated, it cannot have instance data members or methods. It can have only static members. All members are accessed using the class name.
                                    <br />
                                    A static class can be used as a convenient container for sets of methods that just operate on input parameters and do not have to get or set any internal instance fields. A class containing various mathematical operations is a suitable example.
                                    <br /><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
public static class MathOperations
{
    public static int Add(int num1, int num2)
    {
        return num1 + num2;
    }
    public static double Add(double num1, double num2)
    {
        return num1 + num2;
    }
    public static int Subtract(int num1, int num2)
    {
        return num1 - num2;
    }
    public static double Subtract(double num1, double num2)
    {
        return num1 - num2;
    }
}
</pre>
                                        </div>
                                    </div>
                                </p>

                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>-->

                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="String"></a>
                        <h2>String</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="StringIn"></a><strong>String</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/3/2">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                </ul>
                                <p>
                                    System.String class (or its alias,string) represents an immutable string of characters. Methods like Replace(), Insert() etc. that modifies a string actually return a new string containing the modification. Every time any modifications are done on a string a new String object is created.<br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
string message = "Hello! ";
message += "Welcome ";
message += "to ";
message += "Infosys";
</pre>
                                        </div>
                                    </div>
                                </p>

                            </li>
                            <li>
                                <a name="StringBuilder"></a><strong>StringBuilder</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="../Quiz/String.htm">Quiz</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                </ul>
                                <br />
                                <p>
                                    System.Text.StringBuilder class can be used to modify string without creating a new string object
                                    <br />   Available in System.Text Namespace. It has property “Length” and methods Append(), Insert(), Remove() and Replace().
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
StringBuilder message;
message= new StringBuilder();	 
message.Append("Hello! "); 
message.Append("Welcome ");
message.Append("to ");				 
message.Append("Infosys");
</pre>
                                        </div>
                                    </div>
                                </p>

                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>

                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="CodingStandard"></a>
                        <h2>Coding Standard</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="DNetCoding"></a><strong>.NET Coding Standard</strong><br />
                               <br />
                                <p>
                                   Refer the 'DotnetCodingStandards' document provided under Reference Materials -> 'Supplied Files' folder
                                </p>
                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>



                    <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                    <a name="Static"></a>
                    <h2>'static' keyword</h2>
                    <ul class="getStartedList">
                        <li>
                            <a name="Method"></a><strong>Static Members, Constructor and Classes</strong><br />
                            <ul class="horimenu anchorLinks">
                                <li class="last"><a href="http://digitaltutor/#/video/6/3/3">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                <li class="last"><a href="../Demos/BasicCSharp.htm#Static">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                <li class="last"><a href="../Exercises/BasicCSharp.htm#Day1_1">Exercise</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                <li class="last"><a href="../Assignments/BasicCSharp.htm#Day1_2">Assignment</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                            </ul>
                            <p>
                                The “static” keyword can be used for data members, methods, constructors and classes.<br />
                                <br />
                                A static data member is a variable which belongs to the class. A single copy of static data member is shared by all instances of the class. Any modification in value of static data member from one instance will be visible to others.
                                <br /><br />
                                For the use of static variables, creation of instance is not required. Accessed using &lt;class-name&gt;.&lt;variable-name&gt; unlike instance variables which are accessed as &lt;object-name&gt;.&lt;variable-name&gt;.
                                <br /><br />

                                <div class="codesnippet">
                                    <div>
                                        <pre>
public class Category
{
    static short categoryCount = 101;
    short categoryId;
    string categoryName;
    public Category()
    {
        this.categoryId = categoryCount++;
    }
    public Category(string categoryName): this()
    {           
        this.categoryName = categoryName;
    }
}
class Program
{
    static void Main(string[] args)
    {
        Category category1 = new Category(); 
        Category category2 = new Category("Electronics");
    }
}
</pre>
                                    </div>
                                </div>
                            </p>
                            <p>
                                <img src="Images/Static_1.jpg" /><br />
                            </p>
                            Like any static data member, static method belongs to the class (and not to the objects created for the class).  So, it is a class level method. It is accessed using “class_name.method_name”. For using static methods, creation of instance is not necessary.
                            <br /><br /><br />
                            A static method can only access other static data members and static methods. Static methods cannot access instance data members and instance member methods. However, non-static methods can access static data members and static methods.
                            <br /><br />
                            <div class="codesnippet">
                                <div>
                                    <pre>
public class Category
{
    static short categoryCount = 101;
    short categoryId;
    string categoryName;
    public Category()
    {
        this.categoryId = categoryCount++;
    }
    public Category(string categoryName): this()
    {           
        this.categoryName = categoryName;
    }
    public static void PrintNumberOfCategories()
    {
        Console.WriteLine("Number of Categories = " + categoryCount);
    }
    public void PrintCategoryDetails()
    {
        Console.WriteLine("Category Id = " + categoryId);
        Console.WriteLine("Category Name = " + categoryName);
        PrintNumberOfCategories();
    }
}
</pre>
                                </div>
                            </div>
                            <br />
                            <br />
                            Static constructor can be used to perform some action at the very first time a class is loaded. Static constructor for one class is invoked utmost once in the lifetime of the application. It is invoked automatically and cannot be invoked explicitly. <br />
                            The events which can lead to invocation of a static constructor are as follows:<br />
                            <ul>
                                <li>A static method of the class is invoked</li>
                                <li>A static data member of the class is referred</li>
                                <li>An object of the class is created</li>
                            </ul>
                            Creation of a class reference cannot lead to invocation of static constructor.
                            <br />
                            A class can have only one static constructor. Similar to non-static constructors, static constructors also have the same name as the class. Static constructor cannot have any parameter. Static constructor cannot have any access specifiers. It can be used to initialize the static data members of the class.
                            <br /><br />
                            Static Constructors are suitable for those member initializations which need to be done based on some code e.g. if you need to initialize a static data member to a value to be read from a file or database, it can be conveniently done using static constructor.
                            <br /><br />
                            <div class="codesnippet">
                                <div>
                                    <pre>
public class Category
{
    static short categoryCount;
    short categoryId;
    string categoryName;
    static Category()
    {
        //Fetch a value from database and initialize categoryCount
    }
    public Category()
    {
        this.categoryId = categoryCount++;
    }
    public Category(string categoryName): this()
    {           
        this.categoryName = categoryName;
    }
}
</pre>
                                </div>
                            </div><br /><br />
                            In case of inheritance (to be covered later), the static constructor invocation starts from child. This means first the child class static constructor is called followed by parent class.
                            <br /><br />
                            A static class is a class that cannot be instantiated. As it cannot be instantiated, it cannot have instance data members or methods. It can have only static members. All members are accessed using the class name.
                            <br />
                            A static class can be used as a convenient container for sets of methods that just operate on input parameters and do not have to get or set any internal instance fields. A class containing various mathematical operations is a suitable example.
                            <br /><br />
                            <div class="codesnippet">
                                <div>
                                    <pre>
public static class MathOperations
{
    public static int Add(int num1, int num2)
    {
        return num1 + num2;
    }
    public static double Add(double num1, double num2)
    {
        return num1 + num2;
    }
    public static int Subtract(int num1, int num2)
    {
        return num1 - num2;
    }
    public static double Subtract(double num1, double num2)
    {
        return num1 - num2;
    }
}
</pre>
                                </div>
                            </div>
                            </p>

                        </li>
                    </ul>
                    <p><a href="#top">Top of page</a></p>







                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="ParameterTypes"></a>
                        <h2>Parameter Types</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="RefOutParams"></a><strong>'ref', 'out' and 'params' keywords</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/5/0">Assignment</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    <li class="last"><a href="../Demos/BasicCSharp.htm#ParameterTypes">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                    <li class="last"><a href="../Exercises/BasicCSharp.htm#Day2_2">Exercise</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                    <li class="last"><a href="../Assignments/BasicCSharp.htm#Day2_1">Assignment</a></li>&nbsp;&nbsp;&nbsp;&nbsp;     
                               
                                </ul>
                                <p>
                                    In C#, parameters to a method can be passed as:
                                    <ul>
                                        <li>Value</li>
                                        <li>Reference</li>
                                        <li>Output</li>
                                    </ul>
                                   
                                    If no keyword is mentioned along with the parameter, it is passed as Value. If “ref” is mentioned along with the parameter, it is passed as Reference, and if “out” is mentioned it is passed as Output.
                                    <br /><br />
                                    <b> “Passed as Value”</b> indicates that the value of the parameter will be copied to the method. If any changes are made to the value, the changes will not be reflected to the calling environment. This type of parameter passing can be used only to send value to the method.
                                    <br />
                                    A parameter passed as value has to follow these conditions:
                                    <br />
                                    <ul>
                                        <li>should be initialized before the method call</li>
                                        <li>method call can pass direct values or variables</li>
                                    </ul>
                                    <br />
                                    <b> “Passed as Reference”</b> indicates that the reference of the variable, passed as parameter, will be sent to the method. Any changes made to the value of the variable will be made to the same copy as accessed by the calling environment. The changes will hence be reflected to the calling environment. This type of parameter passing can be used to send as well as receive a value to and from a method.
                                    <br />
                                    It should be noted that when a class reference is passed even without using the “ref” keyword, the value of reference is copied. But it continues to refer to the same object and object is not copied. It, hence, behaves as pass as reference.<br />
                                    A parameter passed as reference has to follow these conditions:<br />
                                    <ul>
                                        <li>
                                            should be initialized before the method call
                                        </li>
                                        <li>
                                            ‘ref’ keyword must be specified  both  in method call and in method definition
                                        </li>
                                        <li>
                                            method call cannot pass direct values, only variables can be passed
                                        </li>
                                    </ul>
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
                                                
public void UpdateCategoryName(ref string categoryName)
{
    if (categoryName == "Computers")
    {
        categoryName = "Electronics";
    }
}
</pre>
                                        </div>
                                    </div>
                                    <ul>
                                        <li> A method can have any number of ‘ref’ parameters</li>
                                        <li>
                                            A method can pass any number of values through many ‘ref’ parameters
                                        </li>
                                        <li>
                                            A method can provide any number of result using many ‘ref’ parameters along with a single return value also
                                        </li>
                                        <li>
                                            Try yourself: What will happen, if values are passed directly to ref parameters?
                                        </li>
                                    </ul>
                                    <br /><br /><br />
                                    <b>“Passed as Output”</b> indicates that the variable passed as parameter will be used by the method to store values to be sent back to the calling environment.
                                    <br />
                                    A parameter passed as output has to follow these conditions:
                                    <ul>
                                        <li>need not be initialized before the method call</li>
                                        <li>should be assigned with a value inside the method</li>
                                        <li>‘out’ keyword must be specified both in method call and  in method definition</li>
                                        <li>method call cannot pass direct values, only variables can be passed</li>
                                    </ul>
                                    <br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
public void GetCategoryName(short categoryId, out string categoryName)
{           
    if (categoryId == 101)
    {
        categoryName = "Electronics";
    }
    else if (categoryId == 101)
    {
        categoryName = "Apparels";
    }
    else
    {
        categoryName = "Books";
    }
}
</pre>
                                        </div>
                                    </div>
                                    <br />
                                    <br />
                                    <ul>
                                        <li>A method can have any number of out parameters</li>
                                        <li>
                                            A method can provide result values through many out parameters along with a single return value
                                        </li>
                                        <li>
                                            What will happen, if values are passed directly to OUT parameters?
                                            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Values cannot be passed directly. This will result in compile time error

                                        </li>

                                    </ul>
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
/* Method definition */
void Change1(out int num) 
{
    num = 100;
}
/* Method Call */
Change1( 100 );    //now passing the direct value of 100 to the out parameter will //result complier error
/*Method Definition */
void Change1(out int num) 
{
	num = num + 100;       //Why this will result in error?
}
</pre>
                                        </div>
                                    </div>
                                    <br />
                                    <br />
                                    There are situations when the number of parameters to be passed is unknown at the time of class creation.
                                    <br /><br /><br />
                                    By using the <b>“params” keyword</b> , you can specify a method parameter that takes a variable number of arguments.
                                    You can send a comma-separated list of arguments of the type specified in the parameter declaration or an array of arguments of the specified type. You also can send no arguments. If you send no arguments, the length of the “params” list is zero. No additional parameters are permitted after the “params” keyword in a method declaration, and only one params keyword is permitted in a method declaration.
                                    <br /><br />    <div class="codesnippet">
                                        <div>
                                            <pre>
public void SetEmployeeDetails(int empid, params string[] skills)
{
}
</pre>
                                        </div>
                                    </div>
                                    <br />     The above method can be called in any one of the following ways:
                                    <br /><br />    <div class="codesnippet">
                                        <div>
                                            <pre>
emp.SetEmployeeDetails(1, "C#", "Java", "C++");
emp.SetEmployeeDetails(1);
emp.SetEmployeeDetails(1, "C#");
</pre>
                                        </div>
                                    </div><br /><br />
                                    Consider the following scenario, where there are 2 method overloads:
                                    <br /><br />      <div class="codesnippet">
                                        <div>
                                            <pre>
                                                
public void SetEmployeeDetails(int empid, params string[] skills)
{
}
public void SetEmployeeDetails(int empid)
{
}
</pre>
                                        </div>
                                    </div>
                                    <br /><br />
                                    For the following method call, both the overloads have a match:
                                    <br /><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
                                                
                                                
emp.SetEmployeeDetails(1);
</pre>
                                        </div>
                                    </div><br /><br />
                                    However, since SetEmployeeDetails(int) is clearly a better match than SetEmployeeDetails(int, params string[]),it can be decided without ambiguity that there is a single best match. Hence, SetEmployeeDetails(int) would be called for this method call.
                                    <br />
                                    <br />
                                    It must be a single dimensional array<br />
                                    The ‘params’ keyword must be specified ONLY in the method definition
                                    <br />
                                    <b>Find Yourself: </b>Why Params should be the last parameter?<br />


                                </p>

                            </li>
                            <li>
                                <a name="NamedOptParams"></a><strong>Named and Optional parameters</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="../Demos/BasicCSharp.htm#NamedOptParameter">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                    <li class="last"><a href="../Assignments/BasicCSharp.htm#Day2_2">Additional Assignment</a></li>&nbsp;&nbsp;&nbsp;&nbsp;           
                                   
                                        <li class="last"><a href="../Quiz/ParameterTypes.htm">Quiz</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                </ul>
                                <p>
                                    Introduced in .NET 4.0 <b>Named parameters</b> enables us to pass a value for a particular parameter by associating with the parameter’s name rather than with the parameter's position in the list. When named parameters are used, there is no need to look up or remember the position of each parameter or order of the parameter list (list and order of data types) while calling the method.
                                    <br />While calling a method, the name of a parameter can be associated with the corresponding argument instead of relying on its position

                                    <br />Named parameters can be used with methods, constructors, indexers and delegates

                                    <br />Named Parameters can follow Positional Parameters, but not vice versa

                                    <br />
                                    Calling a method using named parameters is shown below:
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
class UserGreetings
{
       	public void PrintGreetings(string userName, string greetings, int noOfTimes)
       	{
           		for (int i = 1; i <= noOfTimes; i++)
           		{
               		Console.Write(greetings + "! ");
           		}
           		Console.WriteLine(userName);
       	}
}
class Program
{
        static void Main(string[] args)
        {
                UserGreetings userOne = new UserGreetings();
                userOne.PrintGreetings(greetings: "Greetings", userName: "John", noOfTimes:3);
        }
}
</pre>
                                        </div>
                                    </div>
                                    <br />
                                    <b>Optional parameters</b> enables to omit passing values for some parameters in the list. The definition of a method can specify the parameters which are required and which are optional. A call to the method must provide values for all the required parameters but can omit for optional parameters. Optional parameters should be declared at the end of the parameters in the list.
                                    <br />A parameter is declared optional by initializing it to a default value in method signature

                                    <br />Arguments to the Optional Parameters can be omitted during method call

                                    <br />Can be used with methods, constructors, indexers and delegates

                                    <br /> Default values would be used in the called method if a value for optional parameter is not passed. Optional parameters are specified in the method parameter signature by assigning a default value.
                                    <br />
                                    <br />
                                    If the method with optional parameters is called using only named parameters, then the value for the optional parameters should either be passed using named parameters or be omitted<br />
                                    <br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
class UserGreetings
{
    public void PrintGreetings(string userName, string greetings, int noOfTimes=1)
    {
           	for (int i = 1; i <= noOfTimes; i++)
           	{
               	Console.Write(greetings + "! ");
           	}
           	Console.WriteLine(userName);
    }
}
class Program
{
    static void Main(string[] args)
    {
            UserGreetings userOne = new UserGreetings();
            userOne.PrintGreetings(greetings: "Greetings", userName: "John");
    }
}
</pre>
                                        </div>
                                    </div>

                                </p>

                                If the method is called with fixed position of the parameters, then the optional parameters value can either be passed or omitted
                                <br /><br />
                                <div class="codesnippet">
                                    <div>
                                        <pre>
class UserGreetings
{
    public void PrintGreetings(string userName, string greetings, int noOfTimes=1)
    {
           	for (int i = 1; i <= noOfTimes; i++)
           	{
               	Console.Write(greetings + "! ");
           	}
           	Console.WriteLine(userName);
    }
}
class Program
{
    static void Main(string[] args)
    {
            UserGreetings userOne = new UserGreetings();
            userOne.PrintGreetings("John", "Greetings", 5);
    }
}
</pre>
                                    </div>
                                </div><br /><br />
                                If the method is called by using both named and fixed parameters, then the value for optional parameters can either be omitted or passed using only named parameters
                                <br /><br />
                                <div class="codesnippet">
                                    <div>
                                        <pre>
class UserGreetings
{
    public void PrintGreetings(string userName, string greetings, int noOfTimes=1)
    {
           	for (int i = 1; i <= noOfTimes; i++)
           	{
               	Console.Write(greetings + "! ");
           	}
           	Console.WriteLine(userName);
    }
}
class Program
{
    static void Main(string[] args)
    {
            UserGreetings userOne = new UserGreetings();
            userOne.PrintGreetings("John",greetings:"Greetings", 5); //Throws a compilation error
    }
}
</pre>
                                    </div>
                                </div>

                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>


                    <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                    <a name="Tools"></a>
                    <h2>Visual Studio Tools</h2>
                    <ul class="getStartedList">
                        <li>
                            <a name="Debugging"></a><strong>Debugging</strong><br />
                            <ul class="horimenu anchorLinks">
                                <li class="last"><a href="http://digitaltutor/#/video/6/14/0">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                <li class="last"><a href="../Demos/BasicCSharp.htm#Debugging">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                            </ul>
                            <p>
                                Bug is an unintended behavior of a system.<br /> The Process of finding and fixing the bugs is Debugging.<br /> Various levels of bugs:
                                <ul>
                                    <li>
                                        Bugs causing Compile time errors

                                    </li>
                                    <li>
                                        Bugs causing Runtime errors
                                    </li>
                                    <li>
                                        Bugs causing incorrect output of the program


                                    </li>
                                </ul>
                                In order to debug, we would like to see the values of the local variables in the C# program as it executes. This is useful when we want to make sure the values are correct. As we may be interested in a particular part of the code, we need to set a breakpoint somewhere in the block of C# code.
                                <br />     When we set the breakpoint, the debugger will open only if that point is hit. It can be inserted using IDE. It can also be inserted programmatically by the following code:
                                <br />
                                <div class="codesnippet">
                                    <div>
                                        <pre>
System.Diagnostics.Debugger.Break();
</pre>
                                    </div>
                                </div>
                                In Visual Studio, we can inspect the values of variables by using local, auto and watch windows. We can also browse hierarchies of a variable’s internal. We can check the following information about the variables:<br />
                                <ul>
                                    <li>
                                        Name
                                    </li>
                                    <li>
                                        Value
                                    </li>
                                    <li>
                                        Type
                                    </li>
                                </ul>
                                The Locals window shows everything currently in scope. The Autos window is a subset of Locals window and would show only the variables evaluated in current or previous statement during execution.
                                <br />
                                The Watch window is where you can add variables whose value you want to watch. You can add more than just variables, however. You can add any valid expression recognized by the debugger.
                                <br />
                            </p>
                            <p>
                                <img src="Images/Debugging_1.jpg" />
                            </p>
                            The Immediate window is used to debug and evaluate expressions, execute statements, print variable values, and so forth. It allows you to enter expressions to be evaluated or executed by the development language during debugging. <br />
                            <br />
                            <p>
                                <img src="Images/Debugging_2.jpg" />
                            </p>
                            </p>
                        </li>
                        <li>
                            <a name="UnitTesting"></a><strong>Unit Testing</strong><br />
                            <ul class="horimenu anchorLinks">
                                <li class="last"><a href="../Demos/BasicCSharp.htm#UnitTesting">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                            </ul>
                            <p>
                                <br />    In unit testing we check whether a particular module is implemented as per the specification.
                                <br />      Unit testing checks whether coding is correct. A developer is responsible for delivering not simply code as per the requirements, but a Unit Tested Code.
                                <br />  <br />

                                <br />       Unit tests are programmatic tests written in C#. Unit tests are used to exercise other source code by directly calling the methods of a class, passing appropriate parameters. If Assert statements are included, they can test the values that are produced against expected values.

                                <br />       All unit test methods are marked with the [TestMethod()] attribute and are members of the [TestClass()] class.

                                <br />       There are three ways to verify that a unit test has passed:
                                <ul>
                                    <li>
                                        Use one or more Assert statements to validate specific outcomes.

                                    </li>
                                    <li>
                                        Verify that no exception was thrown.

                                    </li>
                                    <li>
                                        Verify that a particular exception is thrown. You can do this by using the ExpectedExceptionAttribute attribute.

                                    </li>
                                </ul>
                                The built-in Testing Tool for Visual Studio contains a number of static methods which can be used to assert correctness at any point in the test. These are static methods of class Assert. They check a condition and reports if it fails. First failing Assertion ends the test.<br />
                                Equality Asserts are methods which test whether the two arguments are equal:<br />
                                <ul>
                                    <li>
                                        Assert.AreEqual(): Tests whether the expected and actual arguments are equal, asserting when they are not equal.

                                    </li>
                                    <li>
                                        Assert.AreNotEqual():Tests whether the expected and actual arguments are equal, asserting when they are equal
                                    </li>
                                </ul>
                                Identity Asserts
                                <ul>
                                    <li>Assert.AreSame(): Tests whether the expected and actual arguments are the same object reference, asserting when they are not the same. </li>
                                    <li>Assert.AreNotSame():Tests whether the expected and actual arguments are the same object reference, asserting when they are the same.</li>
                                </ul>
                                Type Asserts:
                                <ul>
                                    <li>Assert.IsInstanceOfType() : Tests whether the specified object is an instance of the expected type and fails the test if the expected type is not in the inheritance hierarchy of the object. </li>
                                    <li>
                                        Assert.IsNotInstanceOfType():Tests whether the specified object is an instance of the expected type and fails the test if the expected type is in the inheritance hierarchy of the object.

                                    </li>
                                </ul>
                                Condition Asserts are methods used to test a specific condition.
                                <ul>
                                    <li>Assert.IsNull(): Tests whether an object is null </li>
                                    <li>Assert.IsNotNull(): Tests whether an object is not null </li>
                                    <li>Assert.IsTrue(): Tests whether the specified condition is true and fails the test if the condition is false</li>
                                    <li>Inconclusive Assert – This Assert test is used when the conclusion of test is in-deterministic</li>
                                    <li>Assert.Inconclusive(): Denotes a test result that cannot be proven true or false.  </li>
                                </ul>
                                The attribute “ExpectedException” is given to a test method, if it is written to test any method or property that should throw an exception
                            </p>
                        </li>
                        <li>
                            <a name="CodeAnalysis"></a><strong>Code Analysis</strong><br />
                            <ul class="horimenu anchorLinks">
                                <li class="last"><a href="../Demos/BasicCSharp.htm#CodeAnalysis">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                <li class="last"><a href="../Quiz/Tools.htm">Quiz</a></li>&nbsp;&nbsp;&nbsp;&nbsp;


                            </ul>
                            <p>
                                It is important to ensure the code quality in a software development process. Conducting an exhaustive code review is a big challenge.
                                <br />
                                In Visual Studio, it is possible to conduct Automated Code Analysis to examine managed assemblies for design and code correctness
                                <br />
                                Microsoft provides a big library of in-built rules as well. The developer can select/de-select any of these rules. A set of rules chosen to be applied is known as Rule set. A rule set can be applied to multiple applications.
                                <br />
                                It can also be configured whether violation of a rule would throw an error or warning.
                                <br />
                            </p>
                        </li>
                    </ul>
                    <p><a href="#top">Top of page</a></p>



                    <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                    <a name="BoxingUnboxing"></a>
                    <h2>Boxing and Unboxing</h2>
                    <ul class="getStartedList">
                        <li>
                            <a name="IntroInterface"></a><strong>Introduction to Boxing and Unboxing</strong><br />
                            <ul class="horimenu anchorLinks">
                                <li class="last"><a href="http://digitaltutor/#/video/6/8/0">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                <li class="last"><a href="../Demos/BasicCSharp.htm#BoxingUnboxing">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                            </ul>
                            <p>
                                System.Object class is a default parent of all types in C#. This includes value types.
                                Hence, a value of any type can be pointed to by a reference of System.Object. System.Object is aliased as object.
                                <br /><br />
                                When, a value type is pointed by a reference, it needs to be copied on the heap. This is known as boxing.<br />
                                When boxed value type is be again accessed through a value type variable, it has to be copied to stack again. This is known as unboxing.<br /><br />
                                <div class="codesnippet">
                                    <div>
                                        <pre>
int num1 = 10; 
object obj = num1;   //Boxing
int num2 = (int)obj;   //Unboxing
</pre>
                                    </div>
                                </div>
                            </p>
                            <br />
                            Both Boxing and Unboxing are costly in terms of performance. <br />
                        </li>
                    </ul>
                    <p><a href="#top">Top of page</a></p>



                    <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                    <a name="Encapsulation"></a>
                    <h2>Encapsulation</h2>
                    <ul class="getStartedList">
                        <li>
                            <a name="EncapIntro"></a><strong>Introduction to Encapsulation</strong><br />
                            <br />
                            <p>
                                Encapsulation is the ability of an object to hide its internal data and methods, making only the intended parts of the object programmatically accessible. Encapsulation means localization of information of knowledge within an object. It is similar to how a car’s dashboard hides the complexity and internal workings of its engine.
                                <br /><br />
                                Typically in a class:
                                <ul>
                                    <li>State is private (not accessible externally)</li>
                                    <li>Behavior is public (accessible externally)</li>
                                </ul>
                                Let us, with the help of an example, the reason for this.<br /><br />
                                <div class="codesnippet">
                                    <div>
                                        <pre>
class User
{
    public DateTime dateOfBirth;    
} 
User user = new User();
user.dateOfBirth = Convert.ToDateTime("01-Jan-2100"); //Future date
</pre>
                                    </div>
                                </div>
                                <br /><br />
                                As the dateOfBirth is publicly accessible, its value can be set to any valid DateTime, without any restriction.
                                <br /><br />
                                If, instead, dateOfBirth is made private and method is created to Get and Set its value, we can check the value being set.
                                <br /><br /><br />
                                <div class="codesnippet">
                                    <div>
                                        <pre>
class User
{
    private DateTime dateOfBirth;
    public DateTime GetDateOfBirth()
    {
        return dateOfBirth;
    }
    public void SetDateOfBirth(DateTime dateOfBirth)
    {
        if (dateOfBirth < DateTime.Now)
        {
            this.dateOfBirth = dateOfBirth;
        }
    }
} 
</pre>
                                    </div>
                                </div>
                            </p>

                        </li>
                        <li>
                            <a name="Properties"></a><strong>Properties</strong><br />
                            <ul class="horimenu anchorLinks">
                                <li class="last"><a href="http://digitaltutor/#/video/6/6/0">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                <li class="last"><a href="../Demos/BasicCSharp.htm#Properties">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                <li class="last"><a href="../Exercises/BasicCSharp.htm#Day2_1">Exercise</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                


                            </ul>
                            <p>

                                Properties serve the same purpose as get and set methods but syntactically, they are called as data members.
                                <br /><br />
                                For the get and set methods created in the above example, we can have a single property as follows:
                                <br /><br />
                                <div class="codesnippet">
                                    <div>
                                        <pre>
public DateTime DateOfBirth
{
    get { return dateOfBirth; }
    set
    {
        if (value < DateTime.Now)
        {
            dateOfBirth = value;
        }
    }
}
</pre>
                                    </div>
                                </div>

                                While calling, we can use a data member like syntax:
                                <div class="codesnippet">
                                    <div>
                                        <pre>
User user = new User();
user.DateOfBirth = Convert.ToDateTime("01-Jan-2100");  //Will not change the data
user.DateOfBirth = Convert.ToDateTime("01-Jan-1999");  //Will change the data
</pre>
                                    </div>
                                </div>

                                The GET block reads the value of a Data member while SET block writes the value of a data member. “value” is a keyword which gives the value assigned to the property.
                                <br /><br />
                                Property can be made Read-Only, Write-Only and Read-Write by implementing one or both of GET and SET blocks.
                                <br /><br />
                                Property can have only set or only get or both, but should have at least one of these blocks. Not more than one get block and not more than more than one set block can be there.
                                <br /><br />
                            </p>

                        </li>
                        <li>
                            <a name="AutoProp"></a><strong>Auto-Implemented properties</strong><br />
                            <ul class="horimenu anchorLinks">
                                <li class="last"><a href="../Demos/BasicCSharp.htm#AutoProperties">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                            </ul>
                            <p>
                                Supported in C# 3.0 and above
                                <br />Makes property declaration concise
                                <br />Used when no additional logic (i.e., validation logic) is required in the property’s accessors
                                <br />Compiler creates an anonymous and private field(s) based on the property name and can only be accessed through the property's get and set accessors
                                <br />
                                Auto-implemented properties automate the pattern of implementing properties by trivial use of a backing field. <br /> Non-abstract property declarations are allowed to have semicolon accessor bodies.<br />  For such a declared property, a backing field will be automatically generated for it and accessors will be implemented to read from and write to that backing field.<br /> The name of the backing field is compiler generated and inaccessible to the user.
                                <br />Both accessors must be present and both must have semicolon bodies, but they can have different accessibility modifiers
                                <div class="codesnippet">
                                    <div>
                                        <pre>
public class Category
{
    public int CategoryId { get; set; }
    public string CategoryName { get; set; }        
}
class Program
{
    static void Main(string[] args)
    {
        Category category = new Category();
        category.CategoryId = 1;
        category.CategoryName = "Home";
        Console.WriteLine("The category details are:");
        Console.WriteLine("Category ID = " + category.CategoryId);
        Console.WriteLine("Category Name = " + category.CategoryName);
    }
}
</pre>
                                    </div>
                                </div>
                                In the above code snippet, we noticed that there is no validation logic required for the members of the Category class. Hence, instead of declaring member variables, say, categoryId and categoryName, we can directly declare the member properties CategoryId and CategoryName with an abstract get and set accessors. The C# compiler will take care of creating a private and anonymous fields for these two properties. There is no performance improvements that happens with auto-implemented properties, but it only helps the developers to code it easily.
                                <br /><br />
                                <b>
                                    Read-Only Auto-Implemented properties:
                                </b>
                                <br />
                                With auto-implemented properties, both get and set accessors are required. You can create read-only auto-implemented properties by declaring the set accessor of it as private. However, when you declare a private set accessor, you cannot use an object initializer to initialize the property. You may have to use a constructor for initializing. This property, however, can still be modified within the same class where it was declared.
                                <br />
                                <div class="codesnippet">
                                    <div>
                                        <pre>
public class Category
{
    public int CategoryId { get; private set; }
    public string CategoryName { get; set; }
    public Category(int catId)
    {
        CategoryId = catId;
    }
}
class Program
{
    static void Main(string[] args)
    {
        Category category = new Category(1); 
        category.CategoryName = "Home";
        Console.WriteLine("The category details are:");
        Console.WriteLine("Category ID = " + category.CategoryId);
        Console.WriteLine("Category Name = " + category.CategoryName);
    }
}
</pre>
                                    </div>
                                </div>
                                From the above code snippet, it is observed that the CategoryId property is initialized while creating an object of the Category class.<br /> Sometimes, we may have a requirement where in the values of the members should not be initialized explicitly.<br /> Instead, they should be either auto-generated or initialized only at the time of instantiation but not at a later point in time.<br /> In these situations, we can make the set accessor of the corresponding property as private so that they cannot initialize a value for this property outside the class directly.<br /> Hence, we need to create a constructor of a class which initializes the property and thus it becomes a read-only auto-implemented property.
                            </p>

                        </li>
                        <li>
                            <a name="Indexers"></a><strong>Indexers</strong><br />
                            <ul class="horimenu anchorLinks">
                                <li class="last"><a href="http://digitaltutor/#/video/6/6/1">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                <li class="last"><a href="../Demos/BasicCSharp.htm#Indexer">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                <li class="last"><a href="../Exercises/BasicCSharp.htm#Day3_1">Exercise</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                <li class="last"><a href="../Assignments/BasicCSharp.htm#Day3_1">Assignment</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                            </ul>
                            <p>
                                Properties can Read/Write only to a single data item. In order to Read/Write to multiple data items, we can make use of indexers. One indexer can be used to read/write data of only one type. Indexers have one or more index passed to them as parameters. The indices of the indexer can be of different types, which can also lead to overloading of Indexer.
                                <br /><br />
                                Indexer permits members of an instance of a class or struct to be indexed in the same way as elements of array.  Indexers are also made of GET and SET blocks, similar to Properties. The name of the indexer is “this” followed by a parameter list.
                                <br /><br />
                                The signature of indexer is:<br />
                                &lt;modifier&gt; &lt;return type&gt; this [formal argument list]
                                <br /><br />
                                The return type specifies the type of data on which indexer will work. The formal-argument-list specifies the parameters of the indexer.
                                <br />
                                The modifier can be private, public, protected or internal
                                <br />C# do not have the concept of static indexers

                                <br />
                                An example of Indexer with single parameter:
                                <div class="codesnippet">
                                    <div>
                                        <pre>
class Batch
{
    private int[] trainees = new int[100];
    public int this[int index]     // indexer declaration 
    {
        get
        {
            // Check the index limits. 
            if (index < 0 || index >= 100)
            {
                return 0;
            }
            else
            {
                return trainees[index];
            }
        }
        set
        {
            if (!(index < 0 || index >= 100))
            {
                trainees[index] = value;
            }
        }
    }
}
class MainClass
{
    static void Main()
    {
        Batch batch = new Batch();
        // Call the indexer to initialize the elements #2 and #5. 
        batch[2] = 4;
        batch[5] = 32;
        for (int counter = 0; counter <= 10; counter++)
        {
            System.Console.WriteLine("Element #{0} = {1}", counter, batch[counter]);
        }
    }
}
</pre>
                                    </div>
                                </div>
                                The value keyword is used to define the value being assigned by the set indexer<br />
                                Indexers do not have to be indexed by an integer value only; it is up to you how to define the specific look-up mechanism<br />
                                Indexers can have more than one formal parameter, for example, when accessing a two-dimensional array.
                                <br />The get and set accessors are invoked as methods with the parameter list specified in the indexer declaration
                                <br />A base class indexer is inherited to the derived class
                                <br />It can also be overridden in the child class
                                <br />


                                An example of Indexer with two parameters:
                                <div class="codesnippet">
                                    <div>
                                        <pre>
class Batch
{
    private int[] trainees = new int[100];
    private int[] educators = new int[10];
    public int this[int index, string traineeOrEducator]     // indexer declaration 
    {
        get
        {
            if (traineeOrEducator == "Trainee")
            {
                if (index < 0 || index >= 100)
                {
                    return 0;
                }
                else
                {
                    return trainees[index];
                }
            }
            else
            {
                if (index < 0 || index >= 10)
                {
                    return 0;
                }
                else
                {
                    return educators[index];
                }
            }
        }
        set
        {
            if (traineeOrEducator == "Trainee")
            {
                if (!(index < 0 || index >= 100))
                {
                    trainees[index] = value;
                }
            }
            else
            {
                if (!(index < 0 || index >= 10))
                {
                    educators[index] = value;
                }
            }
        }
    }
}
class MainClass
{
    static void Main()
    {
        Batch batch = new Batch();
        batch[2, "Trainee"] = 4;
        batch[5, "Educator"] = 32;
    }
}
</pre>
                                    </div>
                                </div>


                            </p>

                        </li>
                        <li>
                            <a name="PropIndexer"></a><strong>Properties vs Indexers</strong>
                            <ul class="horimenu anchorLinks">
                                <li class="last"><a href="../Quiz/Encapsulation.htm">Quiz</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                            </ul>
                            <p>
                                <table class="content-table">
                                    <tr>
                                        <th>
                                            Indexers
                                        </th>
                                        <th>
                                            Properties
                                        </th>
                                    </tr>
                                    <tr>
                                        <td>
                                            An indexer is identified by its signature.
                                        </td>
                                        <td>
                                            A property is identified by its name.
                                        </td>
                                    </tr>
                                    <tr>
                                        <td>An indexer must be an instance member</td>
                                        <td>Property can be static or an instance member.</td>
                                    </tr>
                                    <tr>
                                        <td>Accessed through an index.</td>
                                        <td>Accessed through a simple name.</td>
                                    </tr>
                                    <tr>
                                        <td>A get block of an indexer has the same formal parameter list as the indexer.</td>
                                        <td>A get block of a property has no parameters.</td>
                                    </tr>
                                    <tr>
                                        <td>A set block of an indexer has the same formal parameter list as the indexer, in addition to the value parameter.</td>
                                        <td>A set block of a property contains the implicit value parameter.</td>
                                    </tr>
                                    <tr>
                                        <td>Allows methods on an object to be called as though the object is an array.</td>
                                        <td>Allows methods to be called as though they were public data members.</td>
                                    </tr>
                                </table>
                            </p>

                        </li>
                    </ul>
                    <p><a href="#top">Top of page</a></p>

                 

                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="Namespace"></a>
                        <h2>Namespace</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="NamespaceIn"></a><strong>Namespace</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/2/0">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                    <li class="last"><a href="../Demos/BasicCSharp.htm#Namespace">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                    <li class="last"><a href="../Quiz/Partial.htm">Quiz</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                </ul>
                                <p>
                                    Consider the case of phone numbers being grouped based on geographical areas.<br /> The common practice is to create area codes and country codes. All phone numbers within an area code should be unique.<br /> All area codes within a country code should be also unique. This facilitates in dialing of phone numbers. A person from the same area should be able to dial a phone with the same area without the need of prefixing area code. Similarly, a person from the same country can dial a phone only by prefixing the area code, without the need of prefixing country code. Only while dialing from outside the country, a person needs to prefix both country code and area code. 
                                <br /><br /><br />
                                    A similar case arises in case of code elements created for an application. <br />When large number of code elements are written in a single application or related applications, it becomes difficult to identify unique names for all elements. In such cases, name clashes can be avoided if elements are grouped into logical hierarchy. The element name should be unique within a logical group. The logical groups are known as namespaces. As it is a hierarchy, namespaces can contain another namespace.
                                    <br />
                                    Assume that there are top level namespaces N1 and N2. Namespace N1 contains namespaces N11, N12, and N2 contains N21 and N22. N22 further contains N221.<br />
                                    <img src="Images/Namespace_1.jpg" />

                                    <br />
                                    The code elements shall now be addressed by using the complete path including namespaces in its path. e.g. N2.N22.N221. It is not always required to use the full path, a relative path would also do. e.g. accessing a code element inside N221 from N21, we can only use N22.N221.


                                    <br />
                                    Namespaces are used for logical organization of code elements. But this introduces the need of using a prefix before the element name in order to access it. The prefix could be long, causing inconvenience in writing code. To avoid this, we can declare some namespaces as default namespaces, where all code elements should be searched:
                                    <br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
using N2.N22.N221;
</pre>
                                        </div>
                                    </div>
                                    If the above statement is used, we need not use a prefix for an element in namespace N2.N22.N221. The code element can be accessed directly.<br /> This works well in most practical cases. However, code element being accessed, should be present only at one of the namespaces being declared with “using” statement.<br /> Otherwise, the program would not know which of the code elements it refers to. 
                                <br />
                                    Ambiguities such as above can be avoided by either giving a fully qualified name (with namespace prefix) or by giving short names to the namespace prefix:<br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
using X= N2.N22.N221;
</pre>
                                        </div>
                                    </div>
                               <br />
                                    The above using clause will allow X to be used in place of the entire prefix N2.N22.N221.<br /> If the namespace is used very often, it could save effort of typing the full name again and again.
                                 </p>
                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>

                        <!--<div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="Tools"></a>
                        <h2>Visual Studio Tools</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="Debugging"></a><strong>Debugging</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/14/0">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    <li class="last"><a href="../Demos/BasicCSharp.htm#Debugging">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                </ul>
                                <p>
                                    Bug is an unintended behavior of a system.<br /> The Process of finding and fixing the bugs is Debugging.<br /> Various levels of bugs:
                                    <ul>
                                        <li>Bugs causing Compile time errors

                                        </li>
                                        <li>Bugs causing Runtime errors
                                        </li>
                                        <li>Bugs causing incorrect output of the program


                                        </li>
                                    </ul>
                                    In order to debug, we would like to see the values of the local variables in the C# program as it executes. This is useful when we want to make sure the values are correct. As we may be interested in a particular part of the code, we need to set a breakpoint somewhere in the block of C# code.
                               <br />     When we set the breakpoint, the debugger will open only if that point is hit. It can be inserted using IDE. It can also be inserted programmatically by the following code:
<br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
System.Diagnostics.Debugger.Break();
</pre>
                                        </div>
                                    </div>
                                    In Visual Studio, we can inspect the values of variables by using local, auto and watch windows. We can also browse hierarchies of a variable’s internal. We can check the following information about the variables:<br />
                                    <ul>
                                        <li>Name
                                        </li>
                                        <li>Value
                                        </li>
                                        <li>Type
                                        </li>
                                    </ul>
                                    The Locals window shows everything currently in scope. The Autos window is a subset of Locals window and would show only the variables evaluated in current or previous statement during execution.
                                <br />
                                    The Watch window is where you can add variables whose value you want to watch. You can add more than just variables, however. You can add any valid expression recognized by the debugger. 
                                <br />
                                    <p>
                                    <img src="Images/Debugging_1.jpg" />
                                        </p>
                                    The Immediate window is used to debug and evaluate expressions, execute statements, print variable values, and so forth. It allows you to enter expressions to be evaluated or executed by the development language during debugging. <br />
                                    <br />
                                <p>
                                    <img  src="Images/Debugging_2.jpg" />
                                </p>
                                </p>
                            </li>
                            <li>
                                <a name="UnitTesting"></a><strong>Unit Testing</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="../Demos/BasicCSharp.htm#UnitTesting">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                </ul>
                                <p>
                                <br />    In unit testing we check whether a particular module is implemented as per the specification.
                                    <br />      Unit testing checks whether coding is correct. A developer is responsible for delivering not simply code as per the requirements, but a Unit Tested Code.
                                    <br />  <br />    

                                    <br />       Unit tests are programmatic tests written in C#. Unit tests are used to exercise other source code by directly calling the methods of a class, passing appropriate parameters. If Assert statements are included, they can test the values that are produced against expected values.

                                    <br />       All unit test methods are marked with the [TestMethod()] attribute and are members of the [TestClass()] class.

                                    <br />       There are three ways to verify that a unit test has passed:
                                    <ul>
                                        <li>Use one or more Assert statements to validate specific outcomes.

                                        </li>
                                        <li>Verify that no exception was thrown.

                                        </li>
                                        <li>Verify that a particular exception is thrown. You can do this by using the ExpectedExceptionAttribute attribute.

                                        </li>
                                    </ul>
                                    The built-in Testing Tool for Visual Studio contains a number of static methods which can be used to assert correctness at any point in the test. These are static methods of class Assert. They check a condition and reports if it fails. First failing Assertion ends the test.<br />
                                    Equality Asserts are methods which test whether the two arguments are equal:<br />
                                    <ul>
                                        <li>Assert.AreEqual(): Tests whether the expected and actual arguments are equal, asserting when they are not equal. 

                                        </li>
                                        <li>Assert.AreNotEqual():Tests whether the expected and actual arguments are equal, asserting when they are equal
                                        </li>
                                    </ul>
                                    Identity Asserts
                                    <ul>
                                        <li>Assert.AreSame(): Tests whether the expected and actual arguments are the same object reference, asserting when they are not the same. </li>
                                        <li>Assert.AreNotSame():Tests whether the expected and actual arguments are the same object reference, asserting when they are the same.</li>
                                    </ul>
                                    Type Asserts: 
                                    <ul>
                                        <li>Assert.IsInstanceOfType() : Tests whether the specified object is an instance of the expected type and fails the test if the expected type is not in the inheritance hierarchy of the object. </li>
                                        <li>Assert.IsNotInstanceOfType():Tests whether the specified object is an instance of the expected type and fails the test if the expected type is in the inheritance hierarchy of the object.

                                        </li>
                                    </ul>
                                    Condition Asserts are methods used to test a specific condition.
                               <ul>
                                   <li>Assert.IsNull(): Tests whether an object is null </li>
                                   <li>Assert.IsNotNull(): Tests whether an object is not null </li>
                                   <li>Assert.IsTrue(): Tests whether the specified condition is true and fails the test if the condition is false</li>
                                   <li>Inconclusive Assert – This Assert test is used when the conclusion of test is in-deterministic</li>
                                   <li>Assert.Inconclusive(): Denotes a test result that cannot be proven true or false.  </li>
                               </ul>
                                    The attribute “ExpectedException” is given to a test method, if it is written to test any method or property that should throw an exception
                                 </p>
                            </li>
                            <li>
                                <a name="CodeAnalysis"></a><strong>Code Analysis</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="../Demos/BasicCSharp.htm#CodeAnalysis">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                    
                                        <li class="last"><a href="../Quiz/Tools.htm">Quiz</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    
                                </ul>
                                <p>
                                    It is important to ensure the code quality in a software development process. Conducting an exhaustive code review is a big challenge.
<br />
                                    In Visual Studio, it is possible to conduct Automated Code Analysis to examine managed assemblies for design and code correctness
                                    <br />                          
                                    Microsoft provides a big library of in-built rules as well. The developer can select/de-select any of these rules. A set of rules chosen to be applied is known as Rule set. A rule set can be applied to multiple applications.
                                    <br />
                                    It can also be configured whether violation of a rule would throw an error or warning.
                                    <br />
                                </p>
                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>-->

                    <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                    <a name="Partial"></a>
                    <h2>'partial' keyword</h2>
                    <ul class="getStartedList">
                        <li>
                            <a name="PartialClass"></a><strong>Partial class</strong><br />
                            <ul class="horimenu anchorLinks">
                                <li class="last"><a href="http://digitaltutor/#/video/6/1/2">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                            </ul>
                            <p>
                                Partial types allow programming elements such as classes to be stored in pieces, in different source files for easier development and maintenance in a team. Different members of the team can work on the same type at the same time by storing them in different files. All such files should be available at the time of compilation.
                                <br /><br />
                                In some cases, that some part of the class is generated by a toll such as Visual Studio and some part is written by the programmer. Partial classes can help achieve this.
                                <div class="codesnippet">
                                    <div>
                                        <pre>
public partial class CoOrds
{
    private int x;
    private int y;
    public CoOrds(int x, int y)
    {
        this.x = x; this.y = y;
    }
}
public partial class CoOrds
{
    public void PrintCoOrds()
    {
        System.Console.WriteLine("CoOrds: {0},{1}",
            x, y);
    }
}
class TestCoOrds
{
    static void Main()
    {
        CoOrds myCoOrds = new CoOrds(10, 15);
        myCoOrds.PrintCoOrds();
    }
} 
</pre>
                                    </div>
                                </div>
                            </p>

                        </li>
                        <li>
                            <a name="PartialMethod"></a><strong>Partial method</strong><br />
                            <br />
                            <p>
                                Partial methods are the code blocks which reside inside a partial type and gets executed only when it has a definition. Partial methods are declared in one partial type (class or struct) and implemented in another partial type. With partial methods, the user may or may not implement the method after it is declared.
                                <br />
                                A partial method can be created by using the keyword ‘partial’. It consists of:
                                <br />

                                Method signature or declaration<br />
                                <div class="codesnippet">
                                    <div>
                                        <pre>
partial void ApplyDiscount();
</pre>
                                    </div>
                                </div>
                                <br />

                                Method implementation or definition
                                <br />
                                <br />
                                <div class="codesnippet">
                                    <div>
                                        <pre>
partial void ApplyDiscount()
{
billAmount = billAmount - (billAmount * 0.2);
}
</pre>
                                    </div>
                                </div>
                                <br />
                                The above may be in separate parts or the same part of the partial class. Including signature and implementation at the same time (when ‘partial’ keyword is used) gives a compilation error. Partial methods are private by default and return type should always be void.
                                <br />
                                <br />
                                <div class="codesnippet">
                                    <div>
                                        <pre>
partial class CalculateBill
{
    double billAmount;
    partial void ApplyDiscount();
}
partial class CalculateBill
{
    public CalculateBill(double billAmount)
    {
        this.billAmount = billAmount;
    }
    partial void ApplyDiscount()
    {
        billAmount = billAmount - (billAmount * 0.2);
    }
    public double GetBillAmount()
    {
        ApplyDiscount();
        return billAmount;
    }
} 
class Program
{
    static void Main(string[] args)
    {
        CalculateBill billOne = new CalculateBill(1000);
        Console.WriteLine("Final bill amount = " + billOne.GetBillAmount());
    }
}
</pre>
                                    </div>
                                </div>
                                <br />
                                The signature of the partial method declaration should match with the method implementation and the method can be implemented only once.
                                <br /><br />
                                The implementation for the partial method is optional as the compiler removes the signature and all calls to the method. Partial methods cannot be called in main because it is private and it can be called only within another method of the same class as shown below:<br /><br />
                                <div class="codesnippet">
                                    <div>
                                        <pre>
partial class CalculateBill
{
    double billAmount;
    partial void ApplyDiscount();
}
partial class CalculateBill
{
    public CalculateBill(double billAmount)
    {
            this.billAmount = billAmount;
    }
    //partial void ApplyDiscount()
    //{
    //    billAmount = billAmount - (billAmount * 0.2);
    //}
    public double GetBillAmount()
    {
            ApplyDiscount();      //Call removed by the compiler
            return billAmount;
    }
}
    
class Program
{
    static void Main(string[] args)
    {
            CalculateBill billOne = new CalculateBill(1000);
            Console.WriteLine("Final bill amount = " + billOne.GetBillAmount());
    }
}
</pre>
                                    </div>
                                </div>
                            </p>

                        </li>
                    </ul>
                    <p><a href="#top">Top of page</a></p>

                    <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                    <a name="Relationship"></a>
                    <h2>Relationship among Classes</h2>
                    <ul class="getStartedList">
                        <li>
                            <a name="RelIntro"></a><strong>Introduction to Relationship</strong><br />
                            <br />
                          <p>
                              The basic idea behind OOP is that the code should resemble the real world objects. This makes the code reusable, readable and maintainable. Most of the times, the real world objects are related to each other and we need to implement the same using appropriate relationships.<br />
                              A few of the relationships among different set of classes are defined below:<br /><br />
                              <ul>
                                  <li>Car is a type of vehicle</li>
                                  <li>A house is made up of Rooms</li>
                                  <li>A Department has several Teachers</li>
                              </ul>
                              <br />
                              Based on the above statements, we can establish a variety of relationships among classes in any object oriented programming languages
                          </p>

                        </li>
                        <li>
                            <a name="UsesA"></a><strong>‘Uses’ Relationship</strong>
                           
                            <p>
                                ‘uses’ relation exists between two classes ‘A’ and ‘B’ only in the following scenarios<br />
                                <ul>
                                    <li>An object of B is passed as argument to a method of A</li>
                                    <li>An object of B is a local variable in a method of A</li>
                                </ul>
                                <br />
                                The life time of B is limited to a particular method where it is being passed-as-argument / declared
                                <br /><br />       It’s the weakest relationship between classes. This type of relationship is known as “Association”.
                                <br />
                                NOTE: In this case, B is not a member (part) of A.<br />
                                <br /><br />

                            </p>

                            <p style="text-align:center">
                                <img src="Images/UsesA_1.jpg" />
                            </p>
                            <br />
                            The code for the above relationship can be explained as follows:
                            <br /><br /><br />
                            <div class="codesnippet">
                                <div>
                                    <pre>
public class Account 
{
     double  balance;
     public double Balance
     {
              get { return balance; }
     }
}
public class ATM 
{
     public void ShowBalance(Account a)  	// Note how the Account class is used here
     {
             Console.WriteLine(“The Account Balance is “ + a.Balance);
     }
}
</pre>
                                </div>
                            </div>
                            </p>

                        </li>
                        <li>
                            <a name="HasA"></a><strong>‘Has-A’ Relationship</strong><br />
                            <br />
                            <p>
                                Whenever there exists a Whole-Part relationship between two classes there exist either aggregation or composition.
                                <br /><br />
                                Aggregation is loosely coupled relationship whereas composition is strongly coupled relationship
                                <br /><br />
                                <strong>Aggregation:</strong><br />
                                <ul>
                                    <li>Here a Whole is made up of 1 or more parts</li>
                                    <li>Part can be added /removed from whole any time, without disturbing its functionality</li>
                                    <li>Whole and part are independent  of each other (one can exist without the other class)</li>
                                </ul>
                                <br /><br />
                                Examples :
                                <br />
                                <table class="content-table">
                                    <tr>
                                        <th>Whole</th>
                                        <th>Part</th>
                                    </tr>
                                    <tr>
                                        <td>Team</td>
                                        <td>Player</td>
                                    </tr>
                                    <tr>
                                        <td>Club</td>
                                        <td>Member</td>
                                    </tr>
                                    <tr>
                                        <td>Library</td>
                                        <td>Book</td>
                                    </tr>
                                    <tr>
                                        <td>Car</td>
                                        <td>MusicPlayer</td>
                                    </tr>
                                </table>
                                <br />
                            </p>
                            <p style="text-align:center">
                                <img src="Images/HasA_1.jpg" />
                            </p><br />
                            The code representing the relationship is given below:<br />
                            <div class="codesnippet">
                                <div>
                                    <pre>
public class MusicPlayer
{
	public string Make { get; set; }
	public string Model { get; set; }
	public double Price { get; set; }
}
public class Car 
{
	public MusicPlayer player;
 	public void AddPlayer(MusicPlayer p)
	{
		player = p;
	}
}
</pre>
                                </div>
                            </div>
                            <br /><br />
                            <strong>Composition:</strong>
                            <br /><br />
                            A variation to the Aggregation relationship is Composition.
                            <br /><br />
                            It is the strongest form of all the association relations. i.e., a stronger relationship than aggregation in whole-part relationships.
                            <br /><br />
                            It’s a Whole-Part relationship where
                            <ul>
                                <li>Whole is responsible for creation and destruction of the parts</li>
                                <li>Part will NOT function independently</li>
                                <li>Whole will NOT function without Part</li>
                            </ul>
                            <br />
                            We cannot add or remove Part at later stage (after making whole)
                            <br />       Part class is an integrated (in separable) part of whole class.
                            <br /><br /><br />
                            <p style="text-align:center">
                                <img src="Images/HasA_2.jpg" />
                            </p><br />
                            <div class="codesnippet">
                                <div>
                                    <pre>
public class Engine
{
	public string Make { get; set; }
	public string Model { get; set; }
	public double Price { get; set; }
}
public class Car 
{
	public Engine theEngine;
	public Car()
	{
 		theEngine = new Engine();
	}
}
</pre>
                                </div>
                            </div>
                            <br />
                            NOTE: The Part constructor should be called inside the constructor of Whole constructor<br />

                            </p>

                        </li>
                        <li>
                            <a name="IsA"></a><strong>‘Is-A’ Relationship</strong>
                            <ul class="horimenu anchorLinks">
                                <li class="last"><a href="../Quiz/Relationship.htm">Quiz</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                            </ul>
                         <p>
                             <i>“Car is a type of Vehicle”</i><br /><br />
                             The above statement demonstrates the relationship between the Vehicle class and the Car class as a parent – child relationship.<br /> The statement says that the Vehicle class exhibits some characteristics and the class Car is a special type of Vehicle class.<br />  And all the characteristics of the Vehicle class can also be accessed using the Car class.<br />  In short, the Vehicle class is generic in nature and the Car class is more specialized one. This type of relationship is called as Inheritance. The inheritance relationship works on two classes – parent class (Vehicle) and the child class (Car). <br /> 
                             <br />
                             The inheritance among the classes are represented in C#:<br /><br />
                             <div class="codesnippet">
                                 <div>
                                     <pre>
class Vehicle
{
	// code for vehicle class comes here…
}
class Car : Vehicle
{
	// code for Car class comes here…
}
class Bus : Vehicle
{
	// code for Bus class comes here…
}

</pre>
                                 </div>
                             </div>
                             <br /><br /><br />
                             <p style="text-align:center">
                                 <img  src="Images/IsA_1.jpg" />
                                 </p>
                         </p>

                        </li>
                     
                     
                    </ul>
                    <p><a href="#top">Top of page</a></p>

                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="Inheritance"></a>
                        <h2>Inheritance</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="InheritanceIntro"></a><strong>Introduction to Inheritance</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/7/0">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    <li class="last"><a href="../Demos/BasicCSharp.htm#Inheritance">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                </ul>
                                <p>
                                    Inheritance follows the “is-a” relationship between classes
                        <br />      The parent class is the base class and the inherited class is the derived class
                              <br />A derived class cannot access the private members of its base class
                                    <br />
             <br />                       Inheritance enables you to create new classes that reuse, extend, and modify the behavior that is defined in other classes. The class whose members are inherited is called the base class, and the class that inherits those members is called the derived class. A derived class can have only one direct base class. However, inheritance is transitive. If ClassC is derived from ClassB, and ClassB is derived from ClassA, ClassC inherits the members declared in ClassB and ClassA.

                                    <br />  <br />                          Conceptually, a derived class is a specialization of the base class. For example, if you have a base class Animal, you might have one derived class that is named Mammal and another derived class that is named Reptile. A Mammal is an Animal, and a Reptile is an Animal, but each derived class represents different specializations of the base class.

                                    <br />      <br />                     When you define a class to derive from another class, the derived class implicitly gains all the members of the base class, except for its constructors and destructors. The derived class can thereby reuse the code in the base class without having to re-implement it. In the derived class, you can add more members. In this manner, the derived class extends the functionality of the base class.

                                    <br />   <br />                       A protected member is accessible only inside its class and its descendants. When a class needs a private member with visibility to its descendant classes, protected access specifier can be used

                                    <br />    <br />                       All the public and protected members of parent class can be accessed in the child class as local members. public member is inherited as a public member by the child class. protected member is inherited as a protected member by the child class.

                                    <br />     <br />                       A sealed class is one that cannot be used as a base class. In other words, a sealed class cannot be extended further by any other class. Classes can be declared as sealed by putting the keyword sealed before the keyword class in the class definition
                                    <br />     
                                </p>

                            </li>
                            <li>
                                <a name="Protected"></a><strong>'protected' access specifier</strong><br />
                              <br />
                                <p>
                                    <ul>
                                        <li>
                                            A protected member is accessible only inside its class and its descendants

                                        </li>
                                        <li>
                                            When a class needs a private member with visibility to its descendant classes, protected access specifier can be used

                                        </li>
                                    </ul>
                                    <div class="codesnippet">
                                        <div>
                                        <pre>
class Employee
{
    private int age;
    protected string name;
    public int salary;
}
class Trainee : Employee
{
        
}

</pre>
                                        </div>
                                    </div>
                                </p>

                            </li>
                            <li>
                                <a name="ConstructorChaining"></a><strong>Constructor chaining</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/7/1">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    <li class="last"><a href="../Demos/BasicCSharp.htm#Chaining">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                </ul>
                                <p>
                                    The parent class constructor will be reused along with child class constructor. Before executing the child class constructor, the parent class constructor must be executed. This is to initialize the inherited data members in the child class during its object creation.
                                    <br /><br />
                                    Whenever a child class object gets created, the parameter-less constructor of base class gets invoked automatically. In case, we wish to invoke some other constructor of base class, we need to do it explicitly:
                                    <br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
class Person
{
    public Person(int personId)
    {
    }
}
class Employee : Person
{
    public Employee(int personId): base(personId)
    {
    }
}

</pre>
                                        </div>
                                    </div>
                                </p>

                            </li>
                            <li>
                                <a name="Sealed"></a><strong>'sealed' modifier</strong><br />
                                
                                <br />
                                <p>
                                    A sealed class is one that cannot be used as a base class.<br />
                                    In other words, a sealed class can not be extended further by any other  class.<br />
                                    Classes can be declared as sealed by putting the keyword sealed before the keyword class in the class definition<br />
                                    <br /><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
sealed class Employee
{
    
}
class Trainee : Employee        //Compile time error : Sealed class cannot be inherited
{
        
}

</pre>
                                        </div>
                                    </div>
                                </p>

                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>

                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="DynamicPoly"></a>
                        <h2>Dynamic Polymorphism</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="Overriding"></a><strong>Method hiding and overriding</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/7/4">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    <li class="last"><a href="../Demos/BasicCSharp.htm#DynamicPoly">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                    <li class="last"><a href="../Exercises/BasicCSharp.htm#Day3_2">Exercise</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                   
                                </ul>
                                <p>
                                    A child class can modify behavior inherited from a parent class<br />
                                    A child class can create a method with different functionality than the parent’s method but with the same:<br />
                                    <ul>
                                        <li>    Name</li>
                                        <li>
                                            Return type
                                        </li>
                                        <li>
                                            Argument list
                                        </li></ul>
                                    A child class method with the same signature can either hide or override  the corresponding parent class method<br />
                                    The keywords used to govern the behavior are:<br />
                                    <ul>
                                        <li>
                                            virtual
                                        </li>
                                        <li>
                                            new
                                        </li>
                                        <li>
                                            override
                                        </li>
                                        <li>
                                            abstract
                                        </li></ul>
                                    <br /><br /><br />
                                    It is possible for the inheriting classes to declare their own variables or methods, which are exactly the same in signature as the inherited classes.<br /><br /><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
class Person
{
    public int commonId = 1000;
    public  void DisplayDetails()
    {
        Console.WriteLine("Person's Id: " + commonId);
    }
}
class Employee : Person
{
    public int commonId = 2000;
    public void DisplayDetails()
    {
        Console.WriteLine("Employee's Id: " + commonId);
    }
}
class Trainee : Employee
{
    public int commonId = 3000;
    public void DisplayDetails()
    {
        Console.WriteLine("Trainee's Id: " + commonId);
    }
}

</pre>
                                        </div>
                                    </div>
                                    <br />
                                    In such cases, by default, the descendant class member is said to be hiding the ancestor class member. 
                                    <br />This means that object of a decedent class will contain the members declared by self as well as defined by ancestors. However, the exact member being used will depend on the reference used to invoke them. The member defined in the class, reference of which is being used, are returned.<br /><br />
                                <div class="codesnippet">
                                    <div>
                                        <pre>
class Program
{
    static void Main(string[] args)
    {
        Person person = new Person();
        person.DisplayDetails();  //Prints 1000
        person = new Employee();
        person.DisplayDetails();  //Prints 1000
        person = new Trainee();
        person.DisplayDetails();  //Prints 1000
        Employee employee = new Employee();
        employee.DisplayDetails(); //Prints 2000
        employee = new Trainee();
        employee.DisplayDetails(); //Prints 2000
        Trainee trainee = new Trainee();
        trainee.DisplayDetails(); //Prints 3000
    }
} 

</pre>
                                    </div>
                                </div>
                                <br />
                                    <br />
                                    In case of members which hide an ancestor class member, it is needed to provide “new” keyword, otherwise a warning is thrown.<br /><br /><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
class Person
{
    public int commonId = 1000;
    public  void DisplayDetails()
    {
        Console.WriteLine("Person's Id: " + commonId);
    }
}
class Employee : Person
{
    public <b>new</b> int commonId = 2000;
    public <b>new</b> void DisplayDetails()
    {
        Console.WriteLine("Employee's Id: " + commonId);
    }
}
class Trainee : Employee
{
    public <b>new</b> int commonId = 3000;
    public <b>new</b> void DisplayDetails()
    {
        Console.WriteLine("Trainee's Id: " + commonId);
    }
}

</pre>
                                        </div>
                                    </div>
                                    <br /><br />
                                    In case of Member Hiding, the called member depends on the reference. At many times in software design, it is needed to call a descendant class method using an ancestor reference.<br /> This gives an advantage of writing the code once for the ancestor, and calling it for any of the descendants by passing the appropriate object at run time.<br />
                                    This is known as Dynamic Method Dispatch and is a kind of Dynamic Polymorphism as the decision about which method to be called is taken at run time.<br />
                                    <br /><br />          Dynamic Method Dispatch is achieved by Method Overriding. More on dynamic method dispatch will be discussed in next section.<br /> Similar to member hiding, a method with the same signature is defined in descendant class.<br /> However, this method is marked with “override” keyword, which means that the descendant class maintains only one copy of the method and that will be called whenever an object of descendant class is used, irrespective of the reference.<br /> In order for descendant to be able to override a method, the ancestor would have declared it as “virtual” or would have overridden it from its ancestor<br />
                                
                                    <br />
                                    As overridden methods are called based on object, they cannot be static.<br /><br />
                                    Below are few more examples for method overriding and hiding:<br /><br />
                                    <b>Method Hiding</b><br /><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
class Program 
{
    static void Main(string[] args) 
    {
        Person person = new Employee();
        person.Hello(); //Prints "Hello Person!" --> Depends on Object
    }
}
class Person {
    public void Hello() { Console.WriteLine("Hello Person!"); }
}
class Employee : Person {
    public new void Hello() { Console.WriteLine("Hello Employee!");}
}

</pre>
                                        </div>
                                    </div>

                                    <br /><br />
                                    <b>Multi-Level Method Overriding</b><br /><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
class Program 
{
    static void Main(string[] args) 
    {
        Person person = new Employee();
        person.Hello(); //Prints "Hello Employee!" --> Depends on Object
    }
}
class Person 
{
    public <b>virtual</b> void Hello() 
    { 
        Console.WriteLine("Hello Person!"); 
    }
}
class Employee : Person 
{
    public <b>override</b> void Hello() 
    { 
        Console.WriteLine("Hello Employee!");
    }
}
</pre>
                                        </div>
                                    </div>
                                    <br />
                                    <br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
class Program 
{
    static void Main(string[] args) 
    {
        Person person = new Trainee();
        person.Hello(); //Prints "Hello Trainee!"
    }
}
class Person 
{
    public <b>virtual</b> void Hello() 
    { 
        Console.WriteLine("Hello Person!"); 
    }
}
class Employee : Person 
{
    public <b>override</b> void Hello() 
    { 
        Console.WriteLine("Hello Employee!");
    }
}
class Trainee: Employee
{
    public <b>override</b> void Hello() 
    { 
        Console.WriteLine("Hello Trainee!");
    }
}
</pre>
                                        </div>
                                    </div>
                                    <br />
                                    <br />
                                    <div class="codesnippet">
                                        <div>
                                     <pre>
class Program 
{
    static void Main(string[] args) 
    {
        Person person = new Trainee();
        person.Hello(); //Prints "Hello Person!"
    }
}
class Person 
{
    public <b>virtual</b> void Hello() 
    { 
        Console.WriteLine("Hello Person!"); 
    }
}
class Employee : Person 
{
    public <b>virtual</b> void Hello() 
    { 
        Console.WriteLine("Hello Employee!");
    }
}
class Trainee: Employee
{
    public <b>override</b> void Hello() 
    { 
        Console.WriteLine("Hello Trainee!");
    }
}
</pre>
                                        </div>
                                    </div>
                                    <br />
                                    <br />
                                    <div class="codesnippet">
                                        <div>
                                          <pre>
class Program 
{
    static void Main(string[] args) 
    {
        Person person = new Trainee();
        person.Hello(); //Prints "Hello Employee!"
    }
}
class Person 
{
    public virtual void Hello() 
    { 
        Console.WriteLine("Hello Person!"); 
    }
}
class Employee : Person 
{
    public override void Hello() 
    { 
        Console.WriteLine("Hello Employee!");
    }
}
class Trainee: Employee
{
    public new void Hello() 
    { 
        Console.WriteLine("Hello Trainee!");
    }
}

</pre>
                                        </div>
                                    </div>
                                    <br />
                                    <br />
                                    <div class="codesnippet">
                                        <div>
                                       <pre>
class Program 
{
    static void Main(string[] args) 
    {
        Person person = new Trainee();
        person.Hello(); // Error
	}
}
class Person 
{
    public virtual void Hello() 
    { 
        Console.WriteLine("Hello Person!"); 
    }
}
class Employee : Person 
{
    public override sealed void Hello() 
    { 
        Console.WriteLine("Hello Employee!");   
    }
}
class Trainee: Employee
{
    public override void Hello() 
    { 
        Console.WriteLine("Hello Trainee!");
    }
}

</pre>
                                        </div>
                                    </div>
                                </p>

                            </li>
                            <li>
                                <a name="MethodDispatch"></a><strong>Dynamic method dispatch</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/7/5">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    <li class="last"><a href="../Demos/BasicCSharp.htm#MethodDispatch">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                  

                                </ul>
                                <p>
                                    <ul>
                                        <li>It is a product of method overriding
</li>
                                        <li>A method is called based on the type of the object pointed by the reference and not on the type of the reference</li>
                                        <li>This decision is taken at runtime and hence known as run time polymorphism
</li>
                                        <li>To achieve dynamic method dispatch

                                            <ul>
                                                <li>Method overriding is a prerequisite </li>
                                                <li>So, inheritance is also a prerequisite
</li>
                                                <li>  Parent class object reference has to point to child/descendant class objects
</li>
                                            </ul>
                                        </li>
                                        <li>Note that the child/descendant class object references can not point to the parent/ancestor class objects</li>
                                        <li>Understanding of Dynamic Method Dispatch helps to design extendable software
</li>
                                    </ul>
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
class Person
{
    int commonId = 1000;
    public virtual void DisplayDetails()
    {
        Console.WriteLine("Person's Id: " + commonId);
    }
}
class Employee : Person
{
    int commonId = 2000;
    public override void DisplayDetails()
    {
        Console.WriteLine("Employee's Id: " + commonId);
    }
}
class Trainee : Employee
{
    int commonId = 3000;
    public override void DisplayDetails()
    {
        Console.WriteLine("Trainee's Id: " + commonId);
    }
}
class Program
{
    static void Main(string[] args)
    {
        Person person = new Person();
        person.DisplayDetails();  //Prints 1000
        person = new Employee();
        person.DisplayDetails();  //Prints 2000
        person = new Trainee();
        person.DisplayDetails();  //Prints 3000
        Employee employee = new Employee();
        employee.DisplayDetails(); //Prints 2000
        employee = new Trainee();
        employee.DisplayDetails(); //Prints 3000
        Trainee trainee = new Trainee();
        trainee.DisplayDetails(); //Prints 3000
    }
}  
</pre>
                                        </div>
                                    </div>
                                </p>
                            </li>
                            <li>
                                <a name="TypeCasting"></a><strong>Type casting</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/7/2">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    <li class="last"><a href="../Demos/BasicCSharp.htm#Casting">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                    <li class="last"><a href="../Assignments/BasicCSharp.htm#Day3_2">Assignment</a></li>&nbsp;&nbsp;&nbsp;&nbsp;           
                                    <li class="last"><a href="../Assignments/BasicCSharp.htm#Day3_3">Additional Assignment</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                   
                                        <li class="last"><a href="../Quiz/DynamicPoly.htm">Quiz</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                 </ul>
                                <p>
                                    A reference of an ancestor class can be used to point to a descendent class object. However, only the members defined in ancestor class can be accessed that case.<br />
                                    <br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
class Person
{
    int personId;
    public int PersonId
    {
        get { return personId; }
        set { personId = value; }
    }
}
class Employee : Person
{
    int employeeId;
    public int EmployeeId
    {
        get { return employeeId; }
        set { employeeId = value; }
    }
}
class Trainee : Employee
{
    int traineeId;
    public int TraineeId
    {
        get { return traineeId; }
        set { traineeId = value; }
    }
}
class Program
{
    static void Main(string[] args)
    {
        Person person = new Trainee();
        Console.WriteLine(person.PersonId);
        Console.WriteLine(person.EmployeeId); //Compile Time error
        Console.WriteLine(person.TraineeId); //Compile Time error
    }
}

</pre>
                                        </div>
                                    </div>
                                <br />
                                    <br />
                                    In order to access the members of descendant class, type casting the reference is required.<br />
                                    <br /><br />
                                     <div class="codesnippet">
                                        <div>
                                            <pre>
static void Main(string[] args)
{
    Person person = new Trainee();
    Console.WriteLine(person.PersonId);
    Trainee trainee = (Trainee)person;
    Console.WriteLine(trainee.EmployeeId); //Not an error
    Console.WriteLine(trainee.TraineeId); //Not an error
}

</pre>
                                        </div>
                                    </div>
                                <br />
                                    <br />
                                    If the reference is type casted to a class which is not an ancestor or the class itself of the object being pointed by the reference, it will be a run time error.
                                    <br />
                                    <br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
static void Main(string[] args)
{
    Person person = new Employee();
    Console.WriteLine(person.PersonId);
    Trainee trainee = (Trainee)person;  //Run time error
}

</pre>
                                        </div>
                                    </div>
                                    <br />
                                    <br />
                                    An alternate way of type casting references is as follows:<br />
                                    <br /><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
static void Main(string[] args)
{
    Person person = new Employee();
    Console.WriteLine(person.PersonId);
    Trainee trainee = person as Trainee; //No run time error
}

</pre>
                                        </div>
                                    </div>
                                    <br /><br />
                                    The above would not throw a run time error. In case type casting is invalid, trainee will be set to null.
<br /><br />
                                    Sometimes the type of object may not be known at compile time:
<br /><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
void DisplayAllDetails(Person person)
{
    //If person points to Person object, display PersonId
    //If person points to Employee object, display PersonId and EmployeeId
    //If person points to Trainee object, display PersonId, EmployeeId and TraineeId
}

</pre>
                                        </div>
                                    </div>
                                    <br />
                                    To avoid the above error, one of the following techniques can be used:<br />
                                    <ul>
                                        <li>Check the object before type-casting:<br /><br />

<div class="codesnippet">
    <div>
        <pre>
void DisplayAllDetails(Person person)
{
    Console.WriteLine(person.PersonId);
    if (person is Employee)
    {
        Console.WriteLine(((Employee)person).EmployeeId);
    }
    if (person is Trainee)
    {
        Console.WriteLine(((Trainee)person).TraineeId);
    }
}

</pre>
    </div>
</div>

                                        </li>
                                        <li>Use “as” operator and check for null:<br /><br />
                                        <div class="codesnippet">
                                            <div>
                                                <pre>
void DisplayAllDetails(Person person)
{
    Console.WriteLine(person.PersonId);
    Employee employee = person as Employee;
    if (employee!=null)
    {
        Console.WriteLine(employee.EmployeeId);
    }
    Trainee trainee = person as Trainee;
    if (trainee!=null)
    {
        Console.WriteLine(trainee.TraineeId);
    }
}

</pre>
                                            </div>
                                        </div>
                                        </li>
                                    </ul>
                                </p>
                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>
    
                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="Types"></a>
                        <h2>Struct and Enum</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="Struct"></a><strong>Struct</strong><br />
                               <br />
                                <p>
                                    “struct” type is a value type that is typically used to encapsulate small groups of related variables, such as the coordinates of a rectangle or the characteristics of an item in an inventory.<br /> The following example shows a simple struct declaration:
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
public struct Category
{
    public short categoryId;
    public string categoryName;
}

</pre>
                                        </div>
                                    </div>
                                    <br />
                                    <br />
                                    Struct is similar to class but unlike class, it is of value type. Structs are copied on assignment. When a struct is assigned to a new variable, all the data is copied, and any modification to the new copy does not change the data for the original copy.
                                    <br /><br />
                                    Following example demonstrates the difference in behavior of class and struct:<br /><br />
                                    <br />
                                    <div class="codesnippet">
                                        <center>

                                            <table class="content-table" style="margin-left:-37px">
                                                <tr>
                                                    <td>
                                                        <pre>
public class Category
{
public short categoryId;
public string categoryName;
}
</pre>
                                                    </td>
                                                    <td>
                                                        <pre>
public struct Category
{
public short categoryId;
public string categoryName;
}
</pre>
                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>
                                                        <pre>
Category el = new Category();
el.categoryId = 101;
el.categoryName = "Electronics";
Category ap = new Category();
ap.categoryId = 102;
ap.categoryName = "Apparels";
el = ap;
//el and ap point to the same object
el.categoryId = 103;
//Changes ap.CategoryId also
el.categoryName = "Books";
//Changes ap.CategoryName also
</pre>
                                                    </td>
                                                    <td>
                                                        <pre>
Category el;
el.categoryId = 101;
el.categoryName = "Electronics";
Category ap;
ap.categoryId = 102;
ap.categoryName = "Apparels";
el = ap; 
//el and ap have the same value but different copies
el.categoryId = 103;
//Does not change ap.CategoryId
el.categoryName = "Books";
//Does not change ap.CategoryName
</pre>
                                                    </td>
                                                </tr>
                                            </table>

                                        </center>
                                    </div>

                                    <br />
                                    A struct can be used as a nullable type and can be assigned a null value by using “?”, as explained earlier.
                                </p>

                            </li>
                            <li>
                                <a name="Enum"></a><strong>Enum</strong><br />
                               <br />
                                <p>
                                    An enum is a set of named integer constants. An enum is a value type. An enum type internally contains an enumerator list.
                                    <br /><br />
                                    An enum can be either declared at the namespace level or inside a class or a struct, It is recommended to declare them within a namespace, so that they can be accessed by all classes that are part of that namespace.
                                    <br /><br />
                                    <b>Syntax:</b><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
enum &lt;enum_name&gt; 
{ 
    enumeration list 
};
</pre>
                                        </div>
                                    </div>
                                    Where,<br />
                                    <ul>
                                                    <li>enum_name specifies the name of the enumeration type</li>
                                                    <li>enumeration list is a comma-separated list of identifiers</li>
</ul>
                                    <br />
                                    <b>
                                        Example - 1:
                                    </b><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
using System;
namespace EnumDemo
{
    enum Mobile { Windows, Android, IOS }
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("I have recently purchased " + Mobile.Android + " phone");
        }
    }
}

</pre>
                                        </div>
                                    </div>
                                   
          <br /><b>Output : </b>I have recently purchased Android phone<br />
                                    <br />
                                    Every enum type has an underlying type, which can be any integral type except char. The default underlying type of enum elements is int.
                                    <br />
                                    <br />
                                    <b>Example - 2:</b>
                                    <br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
namespace EnumDemo
{
    enum Mobile { Windows, Android, IOS }
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("I have recently purchased " + (int)Mobile.Android + " phone");
        }
    }
}

</pre>
                                        </div>
                                    </div>
                                    <br />
                                    <b>Output : </b>I have recently purchased 1 phone<br /><br />
                                    <b>Observation : </b>Default integer value taken by the first enumerated member (i.e., Windows) is zero (0). Hence, when we access the next enumerated value, the output is “1”.<br />
                                    <br />
                                    A variable of type Mobile can be assigned any value based on the underlying type; the values are not limited to the named constants.<br />
                                    <br />
                                    <b>Example - 3 : </b><br /><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
using System;
namespace EnumDemo
{
    enum Mobile { Windows = 7, Android, IOS }
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("I have recently purchased " + (int)Mobile.Android + " phone");
        }
    }
}

</pre>
                                        </div>
                                    </div>
                                    <br />
                                    <br />
                                    <b>Output : </b>I have recently purchased 8 phone<br />
                                    <br />
                                    <b>Observation : </b>We can explicitly assign any integer value to any of the enumerated member. The next member takes a value which is one more than the previous value<br /><br />
                                    <b>Example - 4 :</b>
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
using System;
namespace EnumDemo
{ 
    class Customer
    {
        public enum Mobile { Windows, Android, IOS }
    }
    class Program
    {
        static void Main(string[] args)
        {
            string phone = Customer.Mobile.Windows.ToString();
            Console.WriteLine("A customer has purchased " + phone + " phone");
        }
    }
}

</pre>
                                        </div>
                                    </div>
                                    <br /><br />
                                    An enumerator cannot contain white space in its name. The valid types for an enum are byte, sbyte, short, ushort, int, uint, long, or ulong.
                                    <br /><br />
                                    To declare an enum of another integral type, such as byte, use a colon after the identifier followed by the type, as shown in the following example.
<br /><br />
                                    <div class="codesnippet">
                                        <div>
                                            <pre>
enum Mobile : byte { Windows = 1, Android, IOS }
</pre>
                                        </div>
                                    </div>
                                </p>

                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>

                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="Abstract"></a>
                        <h2>'abstract' keyword</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="AbstractIn"></a><strong>Abstract classes and methods</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/7/6">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    <li class="last"><a href="../Demos/BasicCSharp.htm#Abstract">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                    <li class="last"><a href="../Exercises/BasicCSharp.htm#Day4_2">Exercise</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                    <li class="last"><a href="../Assignments/BasicCSharp.htm#Day4_1">Assignment</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                
                                </ul>
                                <p>
                                    <br />
                                    In some cases, a method is written in parent class only to take advantage of method overriding. <br /><br />The method itself will never be called from the parent class object. In such cases, we may chose not to give body to the method.<br /><br /> Such methods should be declared as abstract and the class containing even a single abstract method should be declared as abstract class.<br /><br /> By declaring a class as abstract, we ensure that the object of class should never be created. This is to prevent the method from being called using the parent class object.
                                    <br /><br />
                                    A non-abstract class can inherit directly or indirectly from the abstract class, but should make all abstract methods should be overridden by non-abstract methods either in the child class or any of its ancestor. In other words, no abstract method should remain un-overridden by a non-abstract method at the time a non-abstract descendent class is created.
                                    <br /><br />
                                    A constructor cannot be declared as abstract.
                                    <br /><br />

                                </p>

                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>

                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="Interface"></a>
                        <h2>Interface</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="IntroInterface"></a><strong>Introduction to Interface</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/7/7">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    <li class="last"><a href="../Demos/BasicCSharp.htm#Interface">Demo</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                </ul>
                                <p>
                                    <ul>
                                        <li>
                                            Interface can be seen as a pure abstract class that contains only abstract methods
                                        </li>
                                        <li>
                                            The child class has to provide the implementation for all the methods of the interface parent
                                        </li>
                                        <li>
                                            Object of an interface cannot be created. However, reference of an interface can be created
                                        </li>
                                        <li>
                                            All methods in an interface are implicitly public and abstract
                                        </li>
                                        <li>
                                            Interface can inherit another interface
                                        </li>
                                        <li>
                                            An access modifier cannot be specified for an interface member.


                                        </li>
                                        <li>A class can implement multiple interfaces but it can inherit only a single class</li>
                                        <li>
                                            Members of an interface can be:

                                            <ul>
                                                <li>Methods</li>
                                                <li>Properties</li>
                                                <li>Indexers</li>
                                            </ul>
                                        </li>
                                        <li>
                                            An interface cannot contain

                                            <ul>
                                                <li>Constants</li>
                                                <li>Fields</li>
                                                <li>Constructors</li>
                                            </ul>
                                        </li>
                                    </ul>
                                </p>

                            </li>
                            <li>
                                <a name="Explicit"></a><strong>Explicit Interface Implementation</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="../Quiz/Interface.htm">Quiz</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                </ul>
                                    <br />
                                    <p>
                                        If a class implements multiple interfaces, it is desirable to prefix the method name with the interface name while overriding this method in a child class. This is known as explicit interface implementation.<br />
                                        <br />
                                        <ul>
                                            <li>
                                                It is used for avoiding name collision
                                            </li>
                                            <li>
                                                It can’t be declared with abstract, virtual, override or new modifiers
                                            </li>
                                            <li>
                                                It can’t have access modifier
                                            </li>
                                            <li>
                                                It cannot be called through concerned object. It can be called only through dynamic binding
                                            </li>
                                            <li>
                                                As a good programming practice, we should use “Explicit interfaces implementation” for all interface implementations
                                            </li>
                                        </ul>
                                    </p>

                                </ul>
                      <p><a href="#top">Top of page</a></p>



                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="Attributes"></a>
                        <h2>Attributes</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="IntroAttribute"></a><strong>Introduction to Attributes</strong><br />
                                <br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/16/0" target="_blank">Video</a></li>

                                </ul>
                                <p>
                                    Attribute is a method of associating declarative information with C# code (types, methods and so forth). Attributes are applied physically before the declaration of a class or member.
                                    <br /><br />
                                    Attributes are used to control runtime behavior. .NET Framework defines a number of standard attributes that can be used to provide functionality, such as serialization, security, and compilation modifications etc.
                                    <br /><br />
                                    An example of pre-defined attribute <b>'Conditional'</b> is given below:
    <br /><br />
    The attribute Conditional enables the definition of conditional methods. The Conditional attribute indicates a condition by testing a conditional compilation symbol. Calls to a conditional method are either included or omitted depending on whether this symbol is defined at the point of the call. If the symbol is defined, the call is included; otherwise, the call (including evaluation of the parameters of the call) is omitted.
    <br /><br />
    In the code below, a class “ClassF” defines the method “F” with conditional attribute. This means that if this method is called, it will execute only if “DEBUG” is declared with #define.
    <br /><br />
    <div class="codesnippet">
        <div>
            <pre>
//File ClassF.cs:
using System.Diagnostics;
class ClassF 
{
   [Conditional("DEBUG")]
   public static void F() 
   {
      Console.WriteLine("Executed ClassF.F");
   }
}
</pre>
        </div>
    </div>
    <br />
    <br />
    In a class “ClassG”, the method F is called after #define DEBUG.<br />
    <br /><br />
    <div class="codesnippet">
        <div>
            <pre>
//File ClassG.cs:
#define DEBUG
class ClassG
{
   public static void G() 
   {
      ClassF.F();            // F is called as DEBUG is defined here
   }
}
</pre>
        </div>
    </div>
    <br />
    <br />
    In a class “ClassH”, the method F is called without #define DEBUG.<br /><br />
    <div class="codesnippet">
        <div>
            <pre>
//File ClassH.cs:
#undef DEBUG
class ClassH
{
   public static void H() 
   {
      ClassF.F();            // F is not called as DEBUG is not defined here
   }
}
</pre>
        </div>
    </div>
    <br />
    <br />
    Attribute <b>‘Obsolete’</b> is used to mark classes and members of classes that can no longer be used
    <br />
    A method can be marked as ‘Obsolete’ as shown below:
    <div class="codesnippet">
        <div>
            <pre>
public class Demo
{
    [Obsolete()]
    public static void OldMethod()
    {
        //Logic to be placed here
    }
    public static void NewMethod()
    {
        //Logic to be placed here
    }
}
</pre>
        </div>
    </div>
    <br />
    When a call is made to the above obsolete method, then a warning is issued as shown below:
    <br />
    <br />
</strong><p style="text-align:center">
                                        <img src="Images/Attributes_1.jpg" />
                                        </p>
                                <br />
                                The above warning message can be customized by using the following syntax:
                                <div class="codesnippet">
                                    <div>
                                        <pre>
public class Demo
{
    [Obsolete("This is an obsolete method, use NewMethod()")]
    public static void OldMethod()
    {
        //Logic to be placed here
    }
    public static void NewMethod()
    {
        //Logic to be placed here
    }
}

</pre>
                                    </div>
                                </div>
                                <br />
                               If an error message is to be displayed instead of a warning, the following syntax can be followed:
                                    <br />
                                <div class="codesnippet">
                                    <div>
                                        <pre>
public class Demo
{
    [Obsolete("This is an obsolete method, use NewMethod()",true)]
    public static void OldMethod()
    {
        //Logic to be placed here
    }
    public static void NewMethod()
    {
        //Logic to be placed here
    }
}

</pre>
                                    </div>
                                </div>
                                    The above examples are given to explain how attributes provide information to compiler and/or runtime environment and would change the compile time and/or runtime behavior. Some other attributes will be discussed under respective topics.<br />
                                    <br />

                                </p>

                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>


                        <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                        <a name="Assemblies"></a>
                        <h2>Assemblies</h2>
                        <ul class="getStartedList">
                            <li>
                                <a name="DNetAssembly"></a><strong>.NET Assembly</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/2/1">Video</a></li>&nbsp;&nbsp;&nbsp;&nbsp;
                                

                                </ul>
                                <p>
                                    An assembly is a basic building block in .NET for code deployment, version control and security. A .NET application results into one or more assemblies on compilation. One assembly can comprise of one or more files.
                                    <br /><br />
                                    There are four important sections of an assembly:
                                    <br />
                                    <ul>
                                        <li>Manifest contains :
                                        <ul><li>The assembly identity  (like name of assembly)</li>
                                            <li>Version</li>
                                            <li>Culture</li>
                                            <li>Digital signature (if the assembly is to be shared across applications)</li>
                                            <li>Names of all files in assembly</li>
                                            <li>The compile-time dependencies on other assemblies</li>
                                            <li>The set of permissions required for the assembly to run properly</li>
                                            </ul></li>
                                        <li>Metadata contains:
                                        <ul>
                                            <li>Description and information of types contained in IL code:
                                            <ul>
                                                <li>Name, visibility, base class, and interfaces implemented. </li>
                                                <li>Members (methods, fields, properties, events, nested types)</li>
                                                </ul></li>
                                            <li>JIT compiler relies on this information to convert IL to native machine code</li>
                                        </ul>
                                        </li>
                                        <li>IL contains: Actual IL code is present in this section</li>
                                        <li>Resources: Additional data e.g. images</li>
                                    </ul>
                                    <br />
                                    <br />
                                    .NET Assemblies on a computer could be one of the following: <br />
                                    <ul>
                                        <li>Private Assembly:
                                        <ul>
                                            <li>The assembly which is used only by a single application</li>
                                            <li>It adds a reference to the class library from its physical location</li>

                                        </ul>
                                        </li>
                                        <li>Shared Assemblies:
                                        <ul>
                                            <li>There could be general-purpose DLL which provides functionality useful in more than one applications.</li>
                                            <li>A common copy of such a DLL can be maintained and shared by all applications</li>
                                            <li>Such assemblies are called as shared assemblies</li>
                                            <li>Global assembly cache is  a special disk folder where all the shared assemblies will be kept</li>
                                            <li>The assembly should be signed with a strong name before putting it into GAC</li>
                                            <li>GAC  permits multiple versions of same assembly to execute  side-by-side
                                            <br />&lt;drive&gt;:\WINDOWS\assembly</li>

                                        </ul>
                                        </li>
                                    </ul>
                                    <p style="text-align:center">
                                    <img src="Images/Assembly_1.jpg" />
                                        </p>
                                    <br />
                                    <br />
                                    To generate strong name using Visual Studio
                                    <br />
                                    <ul>
                                        <li>Solution Explorer -> Right-Click on Project Name -> Select Properties</li>
                                        <li>In the Project Designer-> Click Signing tab</li>
                                        <li>Select Sign the assembly check box</li>
                                        <li>From the drop-down list “Choose a strong name key file”, select &lt;New&gt; </li>
                                        <li>In “Create a strong Name Key”, give key file name</li>
                                        <li>Protect my key File with a Password is not compulsory can be deselected</li>
                                        <li>Click on O.K</li>
                                    </ul>
                                    <br />
                                    Version information and key information is stored in the AssemblyInfo file. Once assembly is built with version and key information, deploy to GAC.  For deploying assembly into GAC use gacutil.exe
                                <br /><br />
                                    gacutil  &lt;the .dll assembly filename&gt;
                                                 <br /><br /> .NET Framework also supports Side-by-side execution. It is Concurrent execution of multiple versions of an assembly either in the same computer or process. This provides the ability to install multiple versions of code. An application can choose which version of the common language runtime or of a component it uses. Even multiple versions of applications can use same version of the .Net Framework
<br /><br />
<p style="text-align:center">                                       
<img src="Images/Assembly_2.jpg"/>
                                </p>
</p>

                            </li>
                            <li>
                                <a name="AccessSpecifier"></a><strong>Access Specifiers</strong><br />
                                <ul class="horimenu anchorLinks">
                                    <li class="last"><a href="http://digitaltutor/#/video/6/4/0" target="_blank">Video</a></li>
                                    <li class="last"><a href="../Exercises/BasicCSharp.htm#Day4_1">Exercise</a></li>
                                   
                                        <li class="last"><a href="../Quiz/AccessSpecifier.htm">Quiz</a></li>&nbsp;&nbsp;&nbsp;&nbsp;

                                    </ul>
                            <p>
                                Following are all the access specifiers in C#:
                                <table class="content-table">
                                    <tr>
                                        <th>If the access specifier is
</th>
                                        <th>Then a member defined in type T and Program A is accessible
</th>
                                    </tr>
                                    <tr>
                                        <td>
                                            public
                                        </td>
                                        <td>
                                            to everyone
                                        </td>
                                    </tr>
                                    <tr>
                                        <td>private</td>
                                        <td>within T only</td>
                                    </tr>
                                    <tr>
                                        <td>protected</td>
                                        <td>to T or types derived from T</td>
                                    </tr>
                                    <tr>
                                        <td>internal</td>
                                        <td>to types within A</td>
                                    </tr>
                                    <tr>
                                        <td>protected internal</td>
                                        <td>to T or types derived from T or to types within A</td>
                                    </tr>
                                </table>
                                <ul>
                                    <li>public – Signifies that the member is accessible from outside the class’s definition and hierarchy of derived classes.</li>
                                    <li>protected – The member isn’t visible outside the class and can be accessed by derived classes only.</li>
                                    <li>private – The member can’t be accessed outside the scope of the defining class. Therefore, not even derived classes have access to these members.</li>
                                    <li>internal – The member is visible only within the current compilation unit. </li>
                                    <li>protected internal – The member is visible in the current assembly and to any derived classes present in another assembly.</li>
                                </ul>
                                Default access specifier for a class member is private and for namespace member is internal

                            </p>


                            </li>
                        </ul>
                        <p><a href="#top">Top of page</a></p>

                    <div class="hr"><img src="../Images/hr-gradient-right-side.jpg" /></div>
                    <a name="RefMaterials"></a>
                    <h2>Other Reference Materials</h2>
                    <ul class="getStartedList">
                        <li>
                            <a name="Presentation"></a><strong>101-001-Slides-BasicCSharpProgramming</strong><br />
                          
                           <p> Basic C Sharp presentation file is available under 'Reference Materials' folder</p>

                        </li>
                        <li>
                            <a name="CaseStudy"></a><strong>Case Study</strong><br />
                           
                            <p>
                                All the documents related to 'Quick Kart' case study is available under Reference Materials -> Supplied Files -> 'Case Study' folder

                            </p>

                        </li>
                        <li>
                            <a name="OtherRef"></a><strong>Other Materials</strong><br />
                       
                            <p>

                                All other neccessary files are provided under Reference Materials -> 'Supplied Files' folder
                            </p>

                        </li>
                   
                    </ul>
                    <p><a href="#top">Top of page</a></p>
                    </div>
                    <!--<div class="vr">
                        <div>
                        </div>
                    </div>-->
                    <div class="clearBoth">
                    </div>
                </div>
            </div>
           
        </div>
   
    <div class="footer">
        <div class="csharpLink">

            <img alt="C Sharp" src="../Images/CSharp-footer.png" />
        </div>
        <div class="leftSideLinks">
            <span>C Sharp Learning Kit</span>
            &nbsp;&nbsp;&nbsp;
            &copy;&nbsp;2015 Infosys
        </div>
    </div>
   
    <dialog id="dialogImage" class="overlay">

        <dd style="text-align:center;vertical-align:middle;position: relative;top: 50%;-webkit-transform: translateY(-50%);-ms-transform: translateY(-50%);transform: translateY(-50%);">

            <div id="ImageViewer" style="text-align:center; vertical-align:middle">

            </div>

        </dd>
        <dd>
            <div>
                <button type="button" class="overlay-close" id="closeImg">Close</button>

            </div>
        </dd>


    </dialog>
    <script src="../Script/Image.js"></script>
    <div id="hidden">
        <div>
            <center>
                <h3 style="color:antiquewhite">Navigate by Topic</h3>
            </center>  
                <ul>
                    <li>
                        <a href="#Framework">.NET Framework</a>
                    </li>
                    <li>
                        <a href="#VS2013">Visual Studio 2013</a>
                    </li>
                    <li>
                        <a href="#ProgrammingBasics">C# Programming Basics</a>
                    </li>
                    <li>
                        <a href="#StaticPoly">Static Polymorphism</a>
                    </li>
                    
                    <li>
                        <a href="#Arrays">Arrays</a>
                    </li>
                    <li>
                        <a href="#Static">'static' keyword</a>
                    </li>
                    <li>
                        <a href="#String">String</a>
                    </li>
                    <li>
                        <a href="#Partial">'partial' keyword</a>
                    </li>
                    <li>
                        <a href="#Namespace">Namespace</a>
                    </li>
                    <li>
                        <a href="#CodingStandard">Coding Standard</a>
                    </li>
                    <li>
                        <a href="#Tools">Visual Studio Tools</a>
                    </li>
                    <li>
                        <a href="#ParameterTypes">Parameter Types</a>
                    </li>
                    <li>
                        <a href="#Encapsulation">Encapsulation</a>
                    </li>
                    
                    
                    <li>
                        <a href="#Relationship">Relationship</a>
                    </li>
                    <li>
                        <a href="#Inheritance">Inheritance</a>
                    </li>
                    <li>
                        <a href="#DynamicPoly">Dynamic Polymorphism</a>
                    </li>
                    <li>
                        <a href="#Abstract">'abstract' keyword</a>
                    </li>
                    <li>
                        <a href="#Types">Struct and Enum</a>
                    </li>
                    
                    <li>
                        <a href="#Interface">Interface</a>
                    </li>
                    <li>
                        <a href="#BoxingUnboxing">
                            Boxing and Unboxing
                        </a>
                    </li>
                    <li>
                        <a href="#Attributes">Attributes</a>
                    </li>
                    <li>
                        <a href="#Assemblies">Assemblies</a>
                    </li>
                </ul>
            
        </div>
    </div>
    <div class="back">
        <a href="../Index.htm" title="Go to TOC"> &laquo;</a>

    </div>
</body>
</html>
