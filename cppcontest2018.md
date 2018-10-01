<blockquote>
<style>html { font-size: 100%; overflow-y: scroll; -webkit-text-size-adjust: 100%; -ms-text-size-adjust: 100%; }

body{
  color:#444;
  font-family:Georgia, Palatino, 'Palatino Linotype', Times, 'Times New Roman',
              "Hiragino Sans GB", "STXihei", "微软雅黑", serif;
  font-size:12px;
  line-height:1.5em;
  background:#fefefe;
  width: 45em;
  margin: 10px auto;
  padding: 1em;
  outline: 1300px solid #FAFAFA;
}

a{ color: #0645ad; text-decoration:none;}
a:visited{ color: #0b0080; }
a:hover{ color: #06e; }
a:active{ color:#faa700; }
a:focus{ outline: thin dotted; }
a:hover, a:active{ outline: 0; }

span.backtick {
  border:1px solid #EAEAEA;
  border-radius:3px;
  background:#F8F8F8;
  padding:0 3px 0 3px;
}

::-moz-selection{background:rgba(255,255,0,0.3);color:#000}
::selection{background:rgba(255,255,0,0.3);color:#000}

a::-moz-selection{background:rgba(255,255,0,0.3);color:#0645ad}
a::selection{background:rgba(255,255,0,0.3);color:#0645ad}

p{
margin:1em 0;
}

img{
max-width:100%;
}

h1,h2,h3,h4,h5,h6{
font-weight:normal;
color:#111;
line-height:1em;
}
h4,h5,h6{ font-weight: bold; }
h1{ font-size:2.5em; }
h2{ font-size:2em; border-bottom:1px solid silver; padding-bottom: 5px; }
h3{ font-size:1.5em; }
h4{ font-size:1.2em; }
h5{ font-size:1em; }
h6{ font-size:0.9em; }

blockquote{
color:#666666;
margin:0;
padding-left: 3em;
border-left: 0.5em #EEE solid;
}
hr { display: block; height: 2px; border: 0; border-top: 1px solid #aaa;border-bottom: 1px solid #eee; margin: 1em 0; padding: 0; }


pre , code, kbd, samp { 
  color: #000; 
  font-family: monospace; 
  font-size: 0.88em; 
  border-radius:3px;
  background-color: #F8F8F8;
  border: 1px solid #CCC; 
}
pre { white-space: pre; white-space: pre-wrap; word-wrap: break-word; padding: 5px 12px;}
pre code { border: 0px !important; padding: 0;}
code { padding: 0 3px 0 3px; }

b, strong { font-weight: bold; }

dfn { font-style: italic; }

ins { background: #ff9; color: #000; text-decoration: none; }

mark { background: #ff0; color: #000; font-style: italic; font-weight: bold; }

sub, sup { font-size: 75%; line-height: 0; position: relative; vertical-align: baseline; }
sup { top: -0.5em; }
sub { bottom: -0.25em; }

ul, ol { margin: 1em 0; padding: 0 0 0 2em; }
li p:last-child { margin:0 }
dd { margin: 0 0 0 2em; }

img { border: 0; -ms-interpolation-mode: bicubic; vertical-align: middle; }

table { border-collapse: collapse; border-spacing: 0; }
td { vertical-align: top; }

@media only screen and (min-width: 480px) {
body{font-size:14px;}
}

@media only screen and (min-width: 768px) {
body{font-size:16px;}
}

@media print {
  * { background: transparent !important; color: black !important; filter:none !important; -ms-filter: none !important; }
  body{font-size:12pt; max-width:100%; outline:none;}
  a, a:visited { text-decoration: underline; }
  hr { height: 1px; border:0; border-bottom:1px solid black; }
  a[href]:after { content: " (" attr(href) ")"; }
  abbr[title]:after { content: " (" attr(title) ")"; }
  .ir a:after, a[href^="javascript:"]:after, a[href^="#"]:after { content: ""; }
  pre, blockquote { border: 1px solid #999; padding-right: 1em; page-break-inside: avoid; }
  tr, img { page-break-inside: avoid; }
  img { max-width: 100% !important; }
  @page :left { margin: 15mm 20mm 15mm 10mm; }
  @page :right { margin: 15mm 10mm 15mm 20mm; }
  p, h2, h3 { orphans: 3; widows: 3; }
  h2, h3 { page-break-after: avoid; }
}
</style>
</blockquote>

<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

# The Contest

I'm something of a collector of C++ esoterica. So for CppCon 2018, I thought it'd be fun to set a challenge to try to collect some more examples of "interesting"-but-valid C++ code:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">I&#39;m running a mini contest during this year&#39;s <a href="https://twitter.com/CppCon?ref_src=twsrc%5Etfw">@CppCon</a>! Show me the most awful, surprising, horrific, inventive, well-formed C++ construct you can fit in a tweet. Best entry as judged by me wins an iPad. <a href="https://twitter.com/hashtag/cppcon?src=hash&amp;ref_src=twsrc%5Etfw">#cppcon</a> <a href="https://twitter.com/hashtag/cppcon2018?src=hash&amp;ref_src=twsrc%5Etfw">#cppcon2018</a></p>&mdash; Richard Smith (@zygoloid) <a href="https://twitter.com/zygoloid/status/1044279153401389056?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

I received over forty entries (most on twitter, with one supplied by email), covering a wide spectrum of awful and awesome constructs.
Thanks to everyone who participated!

It seems there are some common themes that people liked to explore; here's a rundown of some of those themes:

# The Vitriolic

Some people really don't like certain parts of C++.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">std::court &lt;&lt; std::endl;</p>&mdash; Alisdair Meredith (@AlisdairMered) <a href="https://twitter.com/AlisdairMered/status/1044280816656822272?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">std::initializer_list</p>&mdash; Vittorio Romeo (@supahvee1234) <a href="https://twitter.com/supahvee1234/status/1044980731871744006?ref_src=twsrc%5Etfw">September 26, 2018</a></blockquote>

Typo aside, these entries make valid points: both features are easily
misused in various terrible ways, and in the case of `initializer_list`, it
fails to support fundamental parts of modern C++ design, such as move semantics
(and likewise list initialization doesn't support perfect forwarding).

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">The semicolon at the end of each and every expression.</p>&mdash; Apple Tree Mag (SDL) (@stephanedeluca) <a href="https://twitter.com/stephanedeluca/status/1044331395232006146?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

OK, but [popular languages with curly-brace syntax have made worse choices](http://www.bradoncode.com/blog/2015/08/26/javascript-semi-colon-insertion/).

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">otherwise,<br><br>template alias name is its my other alternatives;<br><br>template &lt;typename...&gt; using voidify = void;</p>&mdash; Syahmi SHM (@shahmiBro) <a href="https://twitter.com/shahmiBro/status/1045152726810648576?ref_src=twsrc%5Etfw">September 27, 2018</a></blockquote>

Alias templates definitely have some surprising cases, and this (now known as
`std::void_t`) is a special case of one of them: alias templates that don't use
some or all of their template parameters are *weird*.

# The Vindictive

Some entries want to make future developers' lives miserable with macros.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr"># define true (rand() &gt; 10)<br><br>Happy debugging.</p>&mdash; Arjen Kılıç (@arjnklc) <a href="https://twitter.com/arjnklc/status/1044558526541115392?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr"><a href="https://twitter.com/hashtag/define?src=hash&amp;ref_src=twsrc%5Etfw">#define</a> if(x) if((x) &amp;&amp; rand())<br><br>It&#39;ll almost never matter....</p>&mdash; Jon Simantov (@JonSimantov) <a href="https://twitter.com/JonSimantov/status/1044608640466878465?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="es" dir="ltr">inline T distance_0(const calc&lt;T&gt;&amp; O){<br>#define x (x0+(x3-x0)*.5)<br>#define y (y0+(y3-y0)*.5)<br>#define ox (O.x0+(O.x3-O.x0)*.5)<br>#define oy (O.y0+(O.y3-O.y0)*.5)<br>return sqrt(pow((ox-x),2.0)+pow((oy-y),2.0));<br>#undef x<br>#undef y<br>#undef ox<br>#undef oy<br>}</p>&mdash; Jonatan W (@jawrxu) <a href="https://twitter.com/jawrxu/status/1044324057943019521?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

# The Knights of the Nullary Lambda Calculus

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="fr" dir="ltr">int main()<br>{<br>    [](){}();<br>}</p>&mdash; LokiAstari (@LokiAstari) <a href="https://twitter.com/LokiAstari/status/1044361635622580224?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">I have always been fascinating by how simple lambdas could be:<br><br>[](){}();<br><br>Which actually compiles.</p>&mdash; Michele C. S. (@michelinux) <a href="https://twitter.com/michelinux/status/1044794801193811969?ref_src=twsrc%5Etfw">September 26, 2018</a></blockquote>

Lambdas can of course be simpler: `[]{}` is sufficient.
Sadly we missed the chance in C++20 of allowing `[]<>(){}` -- you need to
declare at least one template parameter in a generic lambda with an explicit
template parameter list.

# The Nearly-Well-Formed

Some decided to submit entries that ignore the "well-formed" requirement. That's OK; I encourage bending (or in this case, entirely breaking) the rules. Others just had minor typos in their examples.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">class X {};<br>class Y {};<br><br>class B {<br>  public:<br>    virtual ~B() = default;<br>    virtual int M(X &amp;);<br>    virtual int M(Y &amp;);<br>};<br><br>class D : public B {<br>  public:<br>    virtual ~D() = default;<br>    int M(X &amp;) override;<br>};<br><br>int Z(Y &amp;y, D &amp;d) {<br>    return d.M(y);<br>}</p>&mdash; Peter Goodman (@peter_a_goodman) <a href="https://twitter.com/peter_a_goodman/status/1045888614100459525?ref_src=twsrc%5Etfw">September 29, 2018</a></blockquote>

Name hiding does not play nicely with virtual function overrides. For more fun, if we had

```class Y : X {};```

... then the code would compile and would call `D::M(X &)`, rather than `B::M(Y &)`.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">// gcc-trunk compiles this :Р<br><br>template &lt;typename R&gt;<br>struct B { <br>  B(R) {}<br>  typedef int t(R);<br>  template &lt;typename U&gt;<br>  t B;<br>};<br><br>template &lt;&gt;<br>template &lt;&gt;<br>int B&lt;int&gt;::B&lt;int&gt;(int) {<br>  // it&#39;s a methstructor!<br>}<br><br>int main() {<br>  B&lt;int&gt;(0).B&lt;int&gt;(0);<br>}</p>&mdash; Eugene Velesevich (@EVelesevich) <a href="https://twitter.com/EVelesevich/status/1045318256691748865?ref_src=twsrc%5Etfw">September 27, 2018</a></blockquote>

matthewbg's law tells us that all software is terrible. Compilers are software; the conclusion is obvious.
A lesser compiler would crash after its initial mistake, but not this one -- it finds a way to make it work.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">int main()<br>{<br>    // URL valid in source :-)<br>    http∶//AmazingSite.com/C++/CoolSyntax <br>    // Note: to work on twitter a small cheat to stop URL shortening.<br>    // I replaced the : (colon) with ∶ (ratio symbol) in the tweet.<br>    // To compile you will need a colon<br>}</p>&mdash; LokiAstari (@LokiAstari) <a href="https://twitter.com/LokiAstari/status/1044525041159819264?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

"Embedding" a URL in source code like this works because the `http:` part is taken as a `goto` label, and the `//` begins a line comment.
However, a `goto` label must be followed by a statement, so this example is actually not valid.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">const char main[] =&quot;\xb8\x2a\x00\x00\x00\xc3&quot;;<a href="https://t.co/Nd4AsBBwCY">https://t.co/Nd4AsBBwCY</a><br><br>Since you allowed a similarly ill-formed one, I will add this one.</p>&mdash; Shafik Yaghmour (@shafikyaghmour) <a href="https://twitter.com/shafikyaghmour/status/1044293832848826369?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">const int main[] = {     -443987883, 440, 113408, -1922629632,     4149, 899584, 84869120, 15544,     266023168, 1818576901, 1461743468, 1684828783,     -1017312735 };</p>&mdash; Ben Harold (@grafcaps) <a href="https://twitter.com/grafcaps/status/1044280851922604032?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

Defining `main` as something other than a function is not actually valid
(because a program is required to have a `main` function, and such a variable
would therefore necessarily constitute an invalid redeclaration of it). This
used to be widely or perhaps universally accepted, but recent versions of both
Clang and GCC reject this.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">// foo_ is a string guarded by mutex mu_. Read it safely.<br>const std::string f = std::lock_guard&lt;std::mutex&gt;(mu_), foo_;</p>&mdash; Aaron Jacobs (@_jacobsa_) <a href="https://twitter.com/_jacobsa_/status/1044455463771729920?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

I believe the intended example here would be more like

```
const std::string f = (std::lock_guard<std::mutex>(mu_), foo_);
```

... which holds the lock during the initialization of `f` and unlocks it at the end of the declaration.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">int main() noexcept(static_cast&lt;bool&gt;(alignof(sizeof(__typeof(std::declval&lt;decltype(__LINE__ || nullptr)&gt;()){})))) {}</p>&mdash; Syahmi SHM (@shahmiBro) <a href="https://twitter.com/shahmiBro/status/1044847190185783296?ref_src=twsrc%5Etfw">September 26, 2018</a></blockquote>

This declares `main` as `noexcept(true)`. It also leans heavily on vendor extensions (both `alignof` applied to an expression and `__typeof` are GNU extensions), but that's not the only non-portable thing happening here: declaring `main` as `noexcept(true)` is not guaranteed to work in C++17 onwards, because the `noexcept` is part of the function type, and the standard doesn't list noexcept function types among the function types that are required to be supported as the type of `main`.

# The Other Subversions of the Rules

Some people found creative ways around the "fits in a tweet" condition. One approach is the godbolt link:

<blockquote class="twitter-tweet" data-conversation="none" data-cards="hidden" data-lang="en"><p lang="en" dir="ltr"><a href="https://t.co/qbz3ARJYHS">https://t.co/qbz3ARJYHS</a><br><br>Aka: lets throw an int from C library callback to interrupt simulation. The int is the error code but it will pass normal catch/throw.</p>&mdash; Petr Hons (@HonsPe) <a href="https://twitter.com/HonsPe/status/1044765797527121921?ref_src=twsrc%5Etfw">September 26, 2018</a></blockquote>

Somewhat more creatively, we have the retweet-of-a-picture-of-the-code strategy:

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">I’m submitting a most wonderful entry to this C++ contest:<a href="https://t.co/AKCuX6Fdiu">https://t.co/AKCuX6Fdiu</a></p>&mdash; JF Bastien (@jfbastien) <a href="https://twitter.com/jfbastien/status/1044288702648770560?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">I believe <a href="https://twitter.com/foonathan?ref_src=twsrc%5Etfw">@foonathan</a> should craft an entry based on his prior efforts. 👌<a href="https://t.co/qU2TLOMvr2">https://t.co/qU2TLOMvr2</a> <a href="https://t.co/j39pSqm1yD">pic.twitter.com/j39pSqm1yD</a></p>&mdash; JF Bastien (@jfbastien) <a href="https://twitter.com/jfbastien/status/1044973151140995072?ref_src=twsrc%5Etfw">September 26, 2018</a></blockquote>

... and the link-to-an-article-describing-the-code strategy:

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">The strlen() function in the string.h library is a piece of marvelous art. It employs vodoo magic, actually.<br>Won&#39;t fit in a tweet but the code is so powerful that it outruns a simple for loop by a great margin. Here: <a href="https://t.co/G6d0p0EHF9">https://t.co/G6d0p0EHF9</a></p>&mdash; Shivam Singhal (@shivasinghal00) <a href="https://twitter.com/shivasinghal00/status/1044360711961370624?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

... and then there's this:

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">As for &quot;surprising, inventive and well-formed C++ construct&quot;, my vote is for<a href="https://t.co/ezzdlQll2v">https://t.co/ezzdlQll2v</a><br>Not sure he will fit in one twit :)</p>&mdash; Kris Kwiatkowski (@_henrycase) <a href="https://twitter.com/_henrycase/status/1044674269417013248?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

... but I'm not sure I want to accept entries that mix C++ and D in that way.

Another option is to describe what the entry would be in words rather than code:

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">Operator overloading is cool if used correctly and if not... OMG. So, few companies ago I&#39;ve seen code with what we called &quot;long arrow concept&quot;. Basically someone did overloading in a way that ---&gt; return pointer which was a pointer to a pointer with a value :)</p>&mdash; Kris Kwiatkowski (@_henrycase) <a href="https://twitter.com/_henrycase/status/1044673641412210688?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

# The Spaghettistas

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">void i() {<br>switch (auto k{i}; true)<br>do if (char j; i) default: ;<br>else ; while (true);<br>}</p>&mdash; JF Bastien (@jfbastien) <a href="https://twitter.com/jfbastien/status/1044844706801356808?ref_src=twsrc%5Etfw">September 26, 2018</a></blockquote>

This is an infinite loop. Notable awful properties:

  * `auto k{i}` declares a function pointer because the function name `i` decays
  * Implicit conversion of function name `i` to `bool` in the `if` condition; the condition evaluates to `true` because the address of `i` is not null
  * `switch` with a non-*compound-statement* body, and a `default:` label nested within an inner control construct (yes, that's valid)
  * Unbraced `do` ... `while` loop with multiple semicolons inside
  * Jump inside the "then" portion of an `if` ... `else` (incidentally, the standard [used to require](http://wg21.link/cwg631) that control flow fall through into the `else` statement in that case!)

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">// towards &quot;portable&quot; MS-style structured exceptions<br>// note that the constructor exits twice!<a href="https://twitter.com/hashtag/include?src=hash&amp;ref_src=twsrc%5Etfw">#include</a> &lt;csetjmp&gt;<a href="https://twitter.com/hashtag/define?src=hash&amp;ref_src=twsrc%5Etfw">#define</a> __try  if(StX x)<a href="https://twitter.com/hashtag/define?src=hash&amp;ref_src=twsrc%5Etfw">#define</a> __except(e) else<br><br>struct StX<br>{<br>  int r;<br>  static std::jmp_buf b;<br>  StX()<br>  {<br>     r=setjmp(b);<br>  }<br>  operator bool(){return !r;}<br>};</p>&mdash; Tony Van Eerd (@tvaneerd) <a href="https://twitter.com/tvaneerd/status/1045798168124948480?ref_src=twsrc%5Etfw">September 28, 2018</a></blockquote>

This ticks a lot of boxes: use of reserved identifiers, simulating exception handling with `setjmp` / `longjmp`, and some light macro abuse. And the worst part is that this also fits into the "almost-useful" category.

# The Almost-Useful

Some entries provided code that's both terrible and does (or appears to do)
something that looks useful.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">template&lt;typename T&gt;<br>struct convert {<br>    template &lt;typename ToType&gt;<br>    constexpr operator ToType() { return static_cast&lt;ToType&gt;(ref); }<br>    constexpr convert(const T&amp; val) : ref{val} {}<br>private:<br>    const T&amp; ref;<br>};<br><br>int main() {<br>    return convert(0.5); //no annoying warning<br>}</p>&mdash; Jakob Hördt (@_neop) <a href="https://twitter.com/_neop/status/1044594017919545345?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">template &lt;auto V&gt;constexpr bool i(){return *(__PRETTY_FUNCTION__ + 14) &gt;&gt; 6;}<br>template &lt;class E, size_t ... D&gt;constexpr auto e(index_sequence&lt;D...&gt;){auto r=0;((i&lt;E(D)&gt;() &amp;&amp; ++r), ...);return r;}<br><br>template &lt;typename E&gt;<br>constexpr auto enum_size = e&lt;E&gt;(make_index_sequence&lt;32&gt;{});</p>&mdash; Jonathan Müller (@foonathan) <a href="https://twitter.com/foonathan/status/1044666286352084992?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

This one needs some explanation: `__PRETTY_FUNCTION__`, on some compilers, will format a non-type template argument of enumeration type using the *name* of the enumerator when one matches. This snippet counts how many integers in [0, 32) are formatted with such a name, and returns that as the "enum size".

The fact that it appears to work, but gets the wrong answer if enumerators are non-contiguous, repeated, or outside the range [0, 32) grants it extra "awful" points.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">template &lt;class...T&gt;<br>struct any_of{<br>  tuple&lt;T...&gt; v;<br>  any_of(T...t):v{t...}{}<br>  template&lt;class U&gt;<br>  bool operator==(U u){<br>    return apply([&amp;](auto...x){return ((x==u)||...);},v);}<br>};<br>template &lt;class...A&gt;<br>any_of(A...)-&gt;any_of&lt;A...&gt;;<br>auto f=[](auto...x) {return any_of{x...}==0;};</p>&mdash; Björn Fahller (@bjorn_fahller) <a href="https://twitter.com/bjorn_fahller/status/1044307110954246145?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

It's hard to say where this falls on the awful/awesome continuum. I wouldn't be surprised if there are branches of mathematics where quantifying a value like this is explored.

# The Lexicographers

Some entries tried to push the C++ lexical rules as far as possible, or maybe a little further:

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">New Kirby operator:<a href="https://twitter.com/hashtag/include?src=hash&amp;ref_src=twsrc%5Etfw">#include</a> &lt;iostream&gt;<br>template&lt;int N&gt; struct x { x() { std::cout &lt;&lt; &quot;poyo&quot;; } };<br><br>int main()<br>{<br>    x &lt;(&#39;o&#39;)&gt; y;<br>}</p>&mdash; Tony Van Eerd (@tvaneerd) <a href="https://twitter.com/tvaneerd/status/1044659853044531200?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

This is reminiscent of the idea of declaring "named operators" by wrapping them in some existing operator token, eg: `vec1 *dot* vec2`.

<blockquote class="twitter-tweet" data-conversation="none" data-cards="hidden" data-lang="en"><p lang="en" dir="ltr">constexpr auto auto​​​​ = auto​​​​​&lt;auto​​,auto​​,auto​​,auto​​,auto​​,auto​​,auto​​&gt;();<br><br>Godbolt <a href="https://t.co/vaHvNETZn7">https://t.co/vaHvNETZn7</a><br><br>All the credit goes to <a href="https://twitter.com/RichardKogelnig?ref_src=twsrc%5Etfw">@RichardKogelnig</a>  for that one <a href="https://t.co/cWo9nwmAZA">https://t.co/cWo9nwmAZA</a></p>&mdash; Shafik Yaghmour (@shafikyaghmour) <a href="https://twitter.com/shafikyaghmour/status/1044590507471466496?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

C++ permits a handful of non-printing Unicode characters in identifiers. This example sneaks in some U+200B ZERO WIDTH SPACE characters to create identifiers that look like the `auto` keyword but are not. Fortunately, [Clang has our back](https://godbolt.org/z/3CfTey).

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">I’d like to also offer this entry to your contest:<a href="https://t.co/Hy3u3LDtMn">https://t.co/Hy3u3LDtMn</a></p>&mdash; JF Bastien (@jfbastien) <a href="https://twitter.com/jfbastien/status/1044292091080204289?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

JF Bastien presents "My Little Lexer: Unicorn is Identifier Character".

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="und" dir="ltr"><a href="https://twitter.com/hashtag/define?src=hash&amp;ref_src=twsrc%5Etfw">#define</a> c̦̰̻̟̰͓͍ơ͓n̪̕s̠͉͎͉͚̞t̘̣͎̯e̯̣͔x̡͙͕͕͈̖͈͈p̲̲̯̲̺r͎̞ constexpr<br><br>c̦̰̻̟̰͓͍ơ͓n̪̕s̠͉͎͉͚̞t̘̣͎̯e̯̣͔x̡͙͕͕͈̖͈͈p̲̲̯̲̺r͎̞ int N = 42;</p>&mdash; nobodyreally (@gamefeast) <a href="https://twitter.com/gamefeast/status/1045150364268343296?ref_src=twsrc%5Etfw">September 27, 2018</a></blockquote>

For when your code really needs that HP Lovecraft feeling.

# The Arithmancers and Demon Summoners

Some chose to have fun with C++'s integer promotion and overflow rules, or to otherwise summon the Nasal Demons.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">Unexpected undefined behavior on most modern platforms:<br><br>void Meow()<br>{<br>    std::uint16_t x = 65535;<br>    x *= x;<br>}<br><br>Undefined behavior on platforms where int=32 and short=16, because * will promote unsigned short to signed int, and then the multiplication overflows signed int.</p>&mdash; Myria (@Myriachan) <a href="https://twitter.com/Myriachan/status/1044284885018468353?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

This is a lovely awful C and C++ quirk.
`x *= x` for built-in type is defined in terms of `x = x * x`,
and `*` performs the usual arithmetic conversions on its operands.
Now, if, as is common across today's implementations, `int` is 32 bits wide,
this means both operands are promoted to `int`,
and the multiplication results in signed overflow
-- and hence in undefined behavior --
if `x > 46340`.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">this is my all-time favorite, it prints a different result depending on whether long ranks higher than unsigned<a href="https://twitter.com/hashtag/include?src=hash&amp;ref_src=twsrc%5Etfw">#include</a> &lt;iostream&gt;<br><br>int main(void) {<br>  std::cout &lt;&lt; (-1L &gt; 1U) &lt;&lt; &quot;\n&quot;;<br>  return 0;<br>}</p>&mdash; John Regehr (@johnregehr) <a href="https://twitter.com/johnregehr/status/1044287345904705536?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

The trick here is that the usual arithmetic conversions care not just about what types you use (`long` versus `unsigned int` in this case), but also the actual sizes of those types on the target. If both types are the same size (eg, on an LLP64 target), the comparison is performed in `unsigned int`, because it can represent larger positive integers. If the types are different sizes (eg, on an LP64 target), the comparison is performed in `long` instead.

So, this innocent-looking code manages to non-portably give an answer that is distinctly different from the mathematical answer. I'm [working with the C++ committee to fix this](http://wg21.link/p0946r0), but it's a long and complex path.

<blockquote class="twitter-tweet" data-conversation="none" data-cards="hidden" data-lang="en"><p lang="en" dir="ltr">Error on Line 0 !!!!<a href="https://twitter.com/hashtag/line?src=hash&amp;ref_src=twsrc%5Etfw">#line</a> 4294967295<br>int main() { return notdefined; }<br><br>Obligatory godbolt: <a href="https://t.co/aS1v0OiZnH">https://t.co/aS1v0OiZnH</a><br><br>h/t <a href="https://twitter.com/CoderCasey?ref_src=twsrc%5Etfw">@CoderCasey</a><a href="https://t.co/Y7sPlzRc1A">https://t.co/Y7sPlzRc1A</a></p>&mdash; Shafik Yaghmour (@shafikyaghmour) <a href="https://twitter.com/shafikyaghmour/status/1045177722471772160?ref_src=twsrc%5Etfw">September 27, 2018</a></blockquote>

A relatively-portable (unsigned) integer overflow in the preprocessor. Pretty swanky.

<blockquote class="twitter-tweet" data-conversation="none" data-cards="hidden" data-lang="en"><p lang="en" dir="ltr">// Infinite loop?<br>for (int i = 0; i &lt; 4; ++i)<br>   std::cout &lt;&lt; i*1000000000 &lt;&lt; std::endl;<br><br>Obligatory godbolt <a href="https://t.co/D6J3ZtSGKs">https://t.co/D6J3ZtSGKs</a><br><br>and Wandbox <a href="https://t.co/MZXJlDsU16">https://t.co/MZXJlDsU16</a><a href="https://t.co/U0K2lWVaKO">https://t.co/U0K2lWVaKO</a></p>&mdash; Shafik Yaghmour (@shafikyaghmour) <a href="https://twitter.com/shafikyaghmour/status/1044472575353442304?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

It's always interesting when a succinct example can demonstrate undefined behavior manifesting in an unusual way. Here, GCC deletes the loop exit condition, because `i >= 4` is impossible after multiplying `i` by 1000000000 and incrementing it.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">Not mine, but:<a href="https://twitter.com/hashtag/include?src=hash&amp;ref_src=twsrc%5Etfw">#include</a> &lt;cstdlib&gt;<br>static void (*f)() = nullptr;<br>void omg() { system(&quot;rm -rf /&quot;); }<br>void not_called() { f = &amp;omg; }<br>int main() { f(); } // calls omg()</p>&mdash; Peter Alexander (@Poita_) <a href="https://twitter.com/Poita_/status/1044652879154475009?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

This is, at this point, a classic: some compilers reason that the only way the call to `f` can be valid is if `not_called` is called first, which means that `main` must call `omg`. Yes, UB can really wipe your hard drive.

# The Reverse Array Indexing Society

Several people submitted entries playing off the fact that the builtin array
subscripting operator is commutative. I received one such entry over email from
Lev Minkowski:

```
int arr[1];
0[arr] = 0;
```

... along with these:

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="sl" dir="ltr">Also valid C:<br><br>int n = sizeof(0)[&quot;abcdefghij&quot;]; printf(&quot;%d\n&quot;, n);<a href="https://t.co/TSQClsaTtg">https://t.co/TSQClsaTtg</a></p>&mdash; Shafik Yaghmour (@shafikyaghmour) <a href="https://twitter.com/shafikyaghmour/status/1044293031203983360?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">int i = 0; while(putchar(i++[&quot;Hello World&quot;]));</p>&mdash; Borislav Stanimirov (@stanimirovb) <a href="https://twitter.com/stanimirovb/status/1044438840402829314?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

This last entry is, for me, the clear winner in this category. The combination
of reverse array indexing, a postincrement expression before the `[`, and
making use of the return value of `putchar` is delectable.

# The Most Surprising

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">Declaring global class within a constructor. It requires a pedantic reading of the standard:<br><br>struct A { void* p; A() : p((struct B*)0) {} };<br>B* bb;</p>&mdash; ofyasy (@cpplearner) <a href="https://twitter.com/cpplearner/status/1044935259001774080?ref_src=twsrc%5Etfw">September 26, 2018</a></blockquote>

This is one of the few entries that had me reaching for my copy of the standard
draft to double-check the rules. Yes, really, a class type declared in a
*mem-initializer* apparently gets introduced in the innermost enclosing
namespace scope (just like a class type declared in the signature of a member
function). GCC, Clang, and ICC all get this "wrong", but MSVC follows the spec.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="und" dir="ltr"><a href="https://t.co/Ju7wRE7UQo">https://t.co/Ju7wRE7UQo</a></p>&mdash; Shafik Yaghmour (@shafikyaghmour) <a href="https://twitter.com/shafikyaghmour/status/1044285910752288769?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

"Of course" this calls the `std::basic_string<CharT>::operator=(CharT)` assignment operator.
Why can `std::string` be assigned from a `char` (given that it can't be constructed from one)?
I have no idea.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">There are functions that can&#39;t be called, because no syntax exist to do that.<br>struct Uncallable {<br>    template &lt;typename T&gt;<br>    Uncallable() { <br>      // You have won<br>   }<br>    <br>    template &lt;typename T&gt;<br>    operator int() {<br>      // You have won<br>    }<br>};</p>&mdash; Piotr Padlewski (@PiotrPadlewski) <a href="https://twitter.com/PiotrPadlewski/status/1044291058778001408?ref_src=twsrc%5Etfw">September 24, 2018</a></blockquote>

This is an odd corner of the language. You never really name a constructor when
calling it, so there's nowhere to provide template arguments. And for a
conversion function, you already have a type after the `operator` keyword, so
even if you call it explicitly (`a.operator X<int>()`), any template arguments
attach to that type, not to the conversion function.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">match&lt;“abc|[0-9]+”&gt;(“1234”);</p>&mdash; Hana Dusíková (@hankadusikova) <a href="https://twitter.com/hankadusikova/status/1044667182041296896?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

This is a reference to Hana's incredible [compile-time regular expression
library](https://github.com/hanickadot/compile-time-regular-expressions).
Or perhaps it's a lamentation about C++'s lack of support for smart quotes.
This is certainly surprising and inventive, but I can't consider it awful
and horrific. Sorry Hana! =)

# The Winner

Congratulations to @foonathan, our overall winner, with this entry:

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">template &lt;auto V&gt;constexpr bool i(){return *(__PRETTY_FUNCTION__ + 14) &gt;&gt; 6;}<br>template &lt;class E, size_t ... D&gt;constexpr auto e(index_sequence&lt;D...&gt;){auto r=0;((i&lt;E(D)&gt;() &amp;&amp; ++r), ...);return r;}<br><br>template &lt;typename E&gt;<br>constexpr auto enum_size = e&lt;E&gt;(make_index_sequence&lt;32&gt;{});</p>&mdash; Jonathan Müller (@foonathan) <a href="https://twitter.com/foonathan/status/1044666286352084992?ref_src=twsrc%5Etfw">September 25, 2018</a></blockquote>

This has everything: it's inventive, appears to be novel (converting
enumeration names to strings via `__PRETTY_FUNCTION__` has been done before,
but this takes it a step further), and manages to do it in an awful way that
looks like it works and passes simple tests but is actually very wrong.

Congratulations Jonathan!
