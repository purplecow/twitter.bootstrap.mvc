twitter.bootstrap.mvc
===================================================

This has the bootstrap layout and supporting files to quickly add [Twitter Bootstrap](http://twitter.github.com/bootstrap/) to an MVC 4 application. <br />

See the overview [blog post](http://lostechies.com/erichexter/2012/11/20/twitter-bootstrap-mvc4-the-template-nuget-package-for-asp-net-mvc4-projects/) for screen shots and features.

To view a working sample, install the [twitter.bootstrap.mvc4.sample](http://nuget.org/packages/twitter.bootstrap.mvc4.sample).

	> Install-Package twitter.bootstrap.mvc4
	> Install-Package twitter.bootstrap.mvc4.sample



**Warning**: After installing the package, you may get build errors.

1. Compiling transformation: The type or namespace name 'Web' does not exist in the namespace 'Microsoft.VisualStudio' (are you missing an assembly reference?) 
2. Compiling transformation: The type or namespace name 'MvcTextTemplateHost' could not be found (are you missing a using directive or an assembly reference?) 

_To resolve these build errors simply close and reopen the solution_


Brought to you by [Eric Hexter](http://lostechies.com/erichexter/)


The automated build is located here: (http://teamcity.codebetter.com/viewType.html?buildTypeId=bt676&tab=buildTypeStatusDiv) Click the "Login as guest" link in the footer of the page.

The preview releases are on this nuget feed (http://www.myget.org/F/erichexter/)

<iframe src="http://teamcity.codebetter.com/externalStatus.html?buildTypeId=bt676&withCss=true"/>