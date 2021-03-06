

   --------------------------------------------------------------------------------
           README file for Web Markup Minifier: ASP.NET 4.X Web Forms v2.3.0

   --------------------------------------------------------------------------------

           Copyright (c) 2013-2017 Andrey Taritsyn - http://www.taritsyn.ru


   ===========
   DESCRIPTION
   ===========
   WebMarkupMin.AspNet4.WebForms contains 5 Web Forms page classes:
   `MinifiedHtmlPage` (supports HTML minification only), `MinifiedXhtmlPage`
   (supports XHTML minification only), `CompressedPage` (supports HTTP compression
   only), `MinifiedAndCompressedHtmlPage` (supports HTML minification and HTTP
   compression) and `MinifiedAndCompressedXhtmlPage` (supports XHTML minification
   and HTTP compression); and 5 master page classes: `MinifiedHtmlMasterPage`
   (supports HTML minification only), `MinifiedXhtmlMasterPage` (supports XHTML
   minification only), `CompressedMasterPage` (supports HTTP compression only),
   `MinifiedAndCompressedHtmlMasterPage` (supports HTML minification and HTTP
   compression) and `MinifiedAndCompressedXhtmlMasterPage` (supports XHTML
   minification and HTTP compression).

   Сlasses of the Web Forms pages and master pages cannot be used together.

   =============
   RELEASE NOTES
   =============
   1. Now, by default, only the `GET` requests are minified and compressed (this
      behavior can be changed by using the `SupportedHttpMethods` property);
   2. Fixed a error of filtering media-types, which led to incorrect usage of HTTP
      compression.

   =============
   DOCUMENTATION
   =============
   See documentation on GitHub - http://github.com/Taritsyn/WebMarkupMin/wiki