# About

<p id="description">K-3D is free-as-in-freedom 3D modeling and animation software. It combines flexible plugins with a visualization pipeline architecture, making K-3D a versatile and powerful tool for artists.</p>

<h2>Easy</h2>

<p>K-3D's interface uses your platform's look-and-feel, and it's consistent with the applications you already know. New artists will find K-3D easy to understand, and professionals feel right at home. K-3D is intuitive, consistent, and discoverable.</p>

<h2>Powerful</h2>

<p>K-3D features procedural and parametric workflows. Properties can be adjusted interactively and results appear immediately. The powerful, node-based visualization pipeline allows more possibilities than traditional modifier stacks or histories. Selection flows from one modifier to the next.</p>

<p>An advanced undo/redo system ensures you can always go back, and the pioneering undo tree means you can always go forward, even where other programs lose the ability to redo.</p>

<p>Industrial-strength standards form the foundation on which K-3D builds - including native RenderMan(TM) support that integrates tightly with the K-3D user interface.</p>

<h2>Flexible</h2>

<p>Get all the power of a node-based visualization pipeline: connect anything to anything else. K-3D gives you the freedom to create combinations never before seen.</p>

<p>Work on one side of a model, show the other side mirrored, and see the end result welded together as a subdivision surface in realtime. Using K-3D, complex workflows are easy to create and understand. Go back, modify the beginning of a workflow, and watch as changes propagate automatically to the end.</p>

<h2>Free</h2>

<p>K-3D is Free Software. Run it on your choice of platform. Adapt it for any purpose. Receive it at no cost. Share it with your friends. All of the K-3D source code is available under the <a href="http://www.gnu.org/licenses/gpl-faq.html">GNU General Public License</a>.</p>

# Developing

<p>K-3D is <a href="http://www.gnu.org/philosophy/free-sw.html">Free Software</a>. The source code is licensed using the <a href="http://www.gnu.org/licenses/gpl-faq.html">GNU General Public License</a>. K-3D is written in C++ with platform independence in mind. As a result, K-3D can be built on <a href="http://www.linux.org">GNU/Linux</a>, <a href="http://www.apple.com">MacOS X</a>, <a href="http://www.freebsd.org/">FreeBSD</a>, <a href="http://www.microsoft.com/windows">Microsoft Windows</a>, and other platforms.</p>

<p>We use <a href="http://git-scm.com/">Git</a> for source-code management, <a href="http://cmake.org">CMake</a> for our build system, and <a href="http://gtkmm.org">gtkmm</a> for our user interface toolkit. Required dependencies include <a href="http://boost.org">Boost</a>, <a href="http://opengl.org">OpenGL</a>, and <a href="http://libsigc.sourceforge.net">libsigc++</a>.</p>

<p>K-3D can be optionally built with integration for Collada, DBus, GLX, Gnome VFS, GTS, ImageMagick, ODE, OpenCASCADE, OpenEXR, and more ...</p>

<h2>Quick Start</h2>

<p><em>Clone the K-3D sources and build:</em></p>

<pre>
$ git clone git://github.com/K-3D/k3d.git
$ mkdir k3d-build
$ cd k3d-build
$ cmake ../k3d
$ make
</pre>

<p><em>Run K-3D from the build directory:</em></p>

<pre>
$ cd k3d-build
$ make run/fast
</pre>

<p><em>Install K-3D:</em></p>

<pre>
$ cd k3d-build
$ make install
</pre>

<p><em>Make changes to the K-3D sources:</em></p>

<ol>
	<li>Create a <a href="http://help.github.com/fork-a-repo/">fork</a> on Github</li>
	<li><a href="http://book.git-scm.com/3_normal_workflow.html">Commit the changes</a></li>
	<li><a href="http://help.github.com/send-pull-requests/">Send a pull request</a></li>
</ol>

<p>You can also just create a patch, if needed.</p>

<p><em>For more on using Git see the <a href="http://book.git-scm.com/">guide</a>.</em></p>

# Donations

<p>K-3D is a member of the nonprofit <a href="http://conservancy.softwarefreedom.org">Software Freedom Conservancy</a>. Thanks to the Conservancy, donations to support K-3D development are convenient, and may be tax-exempt in many jursidictions. The K-3D project uses donations to further our goal of providing quality Free Software for professionals. Thanks in advance for your interest in supporting K-3D!</p>

<h2>PayPal Donations</h2>

<form action="https://www.paypal.com/cgi-bin/webscr" method="post">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="5596283">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>

<h2>Check Donations</h2>

<p>K-3D can accept check donations drawn in USD from banks in the USA. (Donations from banks outside of the US or not in USD should be handled by wire; see <em>Wire Donations</em>).</p>

<p>Donors should make their check payable to:</p>

<pre>
Software Freedom Conservancy, Inc.
</pre>

<p>and place</p>

<pre>
Directed donation: K-3D
</pre>

<p>in the memo field. Checks should then be mailed to:</p>

<pre>
Software Freedom Conservancy
137 Montague Street STE 380
Brooklyn, NY  11201-3548
</pre>

<h2>Wire Donations</h2>

<p>K-3D can accept donations via wire, but instructions must be sent on a case-by-case basis as they are different depending on the country of origin. Donors wishing to send a wire should contact:</p>

<pre>
accounting@sfconservancy.org
</pre>

<p>for instructions. Please be sure to mention that your donation is for K-3D.</p>

# Contact

<p>Help for K-3D is available through the forums or from the mailing list:</p>

<p><a href="https://lists.sourceforge.net/lists/listinfo/k3d-development">https://lists.sourceforge.net/lists/listinfo/k3d-development</a></p>
