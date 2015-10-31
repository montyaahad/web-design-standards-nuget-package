# web-design-standards-nuget-package
The [U.S. Web Design Standards](https://github.com/18F/web-design-standards) is a library of open source UI components and a visual style guide for U.S. federal government websites.

The NuGet Package has been created to access the library easily from Visual Studio NuGet Package Manager.

Go to your Visual Studio Package Manager Console, run the below command.

`PM> Install-Package web-design-standards`

Web design standards css, scripts, images will be under `Content> assets` folder.

Add the following `<link>` and `<script>` elements in your HTML:

    <link rel="stylesheet" href="/Content/assets/css/main.css">
    <link rel="stylesheet" href="/Content/assets/css/google-fonts.css">
    <script src="/Content/assets/js/components.js"></script>
