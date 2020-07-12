# ASP.NET MVC - Useful Links

- Bundling | BundleTable.EnableOptimizations = true; | System.Web.Optimization
    - https://www.tutorialsteacher.com/mvc/stylebundle-mvc
    - https://www.tutorialsteacher.com/mvc/scriptbundle-mvc

- Validation:
    - https://www.tutorialsteacher.com/mvc/implement-validation-in-asp.net-mvc

- Routes
    - Areas: https://www.tutorialsteacher.com/mvc/area-in-asp.net-mvc
	
            - routes.MapRoute(
                    name: "Default",
                    url: "{controller}/{action}/{id}",
                    defaults: new { controller = "Home", action = "Index", id = UrlParameter.Optional }
                );

	- Prevent routes to download
        - https://stackoverflow.com/questions/7715934/how-to-make-all-static-files-like-css-images-js-files-not-be-processed-by-asp-ne

- Filters
	- https://www.tutorialspoint.com/asp.net_mvc/asp.net_mvc_filters.htm
	- https://www.tutlane.com/tutorial/aspnet-mvc/asp-net-filters-action-result-authorization-exception
		
- Return Types of ActionResult and Redirect responses
	- https://www.c-sharpcorner.com/article/action-result-in-asp-net-mvc/
	- HttpStatusCodeResult, HttpUnauthorizedResult, HttpNotFound
			
- CSRF token
	- @Html.AntiForgeryToken()
	- [ValidateAntiForgeryToken]
	- https://www.sjoerdlangkemper.nl/2016/12/22/csrf-protection-by-default-in-asp-net-mvc/
			
- Session Management
	- https://www.c-sharpcorner.com/blogs/manage-session-in-mvc
			
- Http Modules and Http Handlers
	- https://www.c-sharpcorner.com/article/http-handlers-and-http-modules-in-asp-net/
		
- Static files - woff2 (webServer)
		
- Enabling js validation
	- https://www.dotnettricks.com/learn/mvc/how-to-enable-and-disable-client-side-validation-in-mvc#:~:text=Enabling%20and%20Disabling%20Client%2DSide,be%20applied%20to%20application%20level.
	    - <add key="ClientValidationEnabled" value="true" />
		- <add key="UnobtrusiveJavaScriptEnabled" value="true" />
			
- Partial and Action | RenderAction and Render Partial
	- https://dotnet-helpers.com/mvc/difference-between-html-renderpartial-vs-html-partial-and-html-renderaction-vs-html-action-in-mvc/
		
- RenderSection in Layout
    - https://stackoverflow.com/questions/23327578/what-is-rendersection-in-asp-net-mvc

- UI:
    - Dropdown list: https://stackoverflow.com/questions/4833652/asp-net-mvc-with-drop-down-list-and-selectlistitem-assistance
    - Html.BeginForm
    - JSON.Encode/Decode
    - https://www.tutorialsteacher.com/mvc/html-helpers
    - https://www.tutorialsteacher.com/mvc/htmlhelper-editor-editorfor

- web.config 
    - <configuration>
    - system.web
		- authentication
		- customerrors
		- Handlers
		- httpmodules
		- httpCookies 
    - System.webServer
		- Modules
		- Handlers
		- staticContent
    - runtime
    - appsettings
    - connectionStrings
    - configSections
    - elmah
    - entityFramework
    - system.serviceModel
    - system.web.extensions
        - JSON length - serializer