# Awesome Symfony 2 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A list of awesome [Symfony 2](http://symfony.com) bundles, utilities and resources.
d
Table of contents:

* [User Management](#user-management)
* [Web Services](#web-services)
* [Template Engine](#template-engine)
* [Storage](#storage)
* [Validation](#validation)
* [Forms](#forms)
* [Service Container](#service-container)
* [Development](#development)
* [Assets Management](#assets-management)
* [Queues](#queues)
* [Internationalization](#internationalization)
* [Payments Management](#payments-management)
* [Monitoring](#monitoring)
* [Miscellaneous](#miscellaneous)
* [Third Party APIs](#third-party-apis)
* [Reading](#reading)
* [Distributions](#distributions)

## User Management

 * [FOSUserBundle](https://github.com/FriendsOfSymfony/FOSUserBundle) - Adds support for a database-backed user system.
 * [HWIOAuthBundle](https://github.com/hwi/HWIOAuthBundle) - OAuth client integration. Supports both OAuth1.0a and OAuth2.
 * [JmikolaAutoLoginBundle](https://github.com/jmikola/JmikolaAutoLoginBundle) - This bundle integrates the AutoLogin library with Symfony2, which implements a security firewall listener to authenticate users based on a single query parameter.
 * [JMSSecurityExtraBundle](http://jmsyst.com/bundles/JMSSecurityExtraBundle) - Enhances the Security Component with several new features.

## Web Services

 * [BazingaHateoasBundle](https://github.com/willdurand/BazingaHateoasBundle) - Integration of the Hateoas library.
 * [FOSOAuthServerBundle](https://github.com/FriendsOfSymfony/FOSOAuthServerBundle) - A server side OAuth2 bundle.
 * [FOSRestBundle](https://github.com/FriendsOfSymfony/FOSRestBundle) - Provides various tools to rapidly develop RESTful API's & applications.
 * [JMSSerializerBundle](https://github.com/schmittjoh/JMSSerializerBundle) - Easily serialize, and deserialize data of any complexity.
 * [JSONApiBundle](https://github.com/nilportugues/symfony2-jsonapi-transformer) - Bundle which provides support for formatting REST reponses to follow the JSON API specification.
 * [KnpJsonSchemaBundle](https://github.com/KnpLabs/KnpJsonSchemaBundle) - Provide a service which allow you to generate json schema based on validation metadata.
 * [LexikJWTAuthenticationBundle](https://github.com/lexik/LexikJWTAuthenticationBundle) - This bundle provides JWT (Json Web Token) authentication for your REST API using the namshi/jose library.
 * [NelmioApiDocBundle](https://github.com/nelmio/NelmioApiDocBundle) - Generates documentation for your REST API from annotations.
 * [NelmioCorsBundle](https://github.com/nelmio/NelmioCorsBundle) - Adds ability to add CORS-related headers based on simple ACL-style per-URL configurations.
 * [RateLimitBundle](https://github.com/jaytaph/RateLimitBundle) - Add rate limits to your controllers/actions easily through annotations.
 * [RequestLimitBundle](https://github.com/zim32/Symfony2-RequestLimitBundle) - With this bundle you can easy limit requests to your application.
 * [ResourceBundle](https://github.com/ProgrammingAreHard/ResourceBundle) - Bundle that helps in developing REST APIs.
 * [SerializedResponseBundle](https://github.com/Pulpmedia/SerializedResponseBundle) - A simple bundle to provide an easy way to send out json/xml/yaml responses of serialized objects with annotations.
 * [LemonRestBundle](https://github.com/stanlemon/rest-bundle) - An opinionated bundle providing REST endpoints for Doctrine entities

## Template Engine

 * [CgKintBundle](https://github.com/barelon/CgKintBundle) - This bundle lets you use the Kint library in your Twig templates.
 * [FlashAlertBundle](https://github.com/rasanga/FlashAlertBundle) - Simplified way to handle (add/display) Symfony flash messages.
 * [GravatarBundle](https://github.com/ornicar/GravatarBundle) - Simple wrapper to gravatar API.
 * [KnpTimeBundle](https://github.com/KnpLabs/KnpTimeBundle) - Provides helpers for time manipulation.
 * [TwigCacheBundle](https://github.com/EmanueleMinotto/TwigCacheBundle) - Bundle for asm89/twig-cache-extension.
 * [TwigExtraBundle](https://github.com/csanquer/TwigExtraBundle) - Twig Extra Tools Extensions.
 * [TwigInflectionBundle](https://github.com/EmanueleMinotto/TwigInflectionBundle) - Apply inflection via a Twig extension.
 * [TwigJackBundle](https://github.com/boekkooi/TwigJackBundle) - Handy additional features for Twig.
 * [TwitalBundle](https://github.com/goetas/twital-bundle) - An attribute template engine built on top of Twig and 100% compatible with all twig's features.
 * [UcoTwigExtensionsBundle](https://github.com/sgomez/UcoTwigExtensionsBundle) - Provides some filters.

## Storage

 * [AliceBundle](https://github.com/hautelook/AliceBundle) A Symfony2 bundle to help load Doctrine Fixtures with Alice.
 * [AliceFixturesBundle](https://github.com/h4cc/AliceFixturesBundle) - A Symfony2 bundle for using Alice and Faker with data fixtures.
 * [doctrine-routing-bundle](https://github.com/eschmar/doctrine-routing-bundle) - Dynamic database routing.
 * [DoctrineEncryptBundle](https://github.com/vmelnik-ukraine/DoctrineEncryptBundle) - Bundle allows you to create doctrine entities with fields that will be protected by encryption algorithms such as AES.
 * [DoctrineEnumBundle](https://github.com/fre5h/DoctrineEnumBundle) - Provides support of MySQL ENUM type for Doctrine2.
 * [DoctrineFixturesBundle](https://github.com/doctrine/DoctrineFixturesBundle) - Integrates the Doctrine2 Data Fixtures library.
 * [DoctrineMigrationsBundle](https://github.com/doctrine/DoctrineMigrationsBundle) - Integrates the Doctrine2 Migrations library.
 * [elastica-query-bundle](https://github.com/mapado/elastica-query-bundle) - Query builder bundle for ElasticSearch.
 * [FeedBundle](https://github.com/eko/FeedBundle) - A bundle to build RSS feeds from your entities.
 * [FPNTagBundle](https://github.com/FabienPennequin/FPNTagBundle) - This bundle adds tagging, with the ability to associate tags with any number of different entities.
 * [GaufretteBrowserBundle](https://github.com/digitalkaoz/GaufretteBrowserBundle) - This Bundle allows you to browse a Gaufrette Filesystem like a Doctrine Connection.
 * [KnpGaufretteBundle](https://github.com/KnpLabs/KnpGaufretteBundle) - Integrates Gaufrette.
 * [MysqlDoctrineFunctions](https://github.com/mapado/MysqlDoctrineFunctions) - MySQL Function for Doctrine : RAND(), ROUND() DATE(), DATE_FORMAT().
 * [OneupFlysystemBundle](https://github.com/1up-lab/OneupFlysystemBundle) - Integrates Flysystem.
 * [RelationBundle](https://github.com/Ph3nol/RelationBundle) - Bundle to manage relations between models/entities. (Not maintained anymore)
 * [SncRedisBundle](https://github.com/snc/SncRedisBundle) - Bundle to integrate Redis into your app.
 * [StofDoctrineExtensionsBundle](https://github.com/stof/StofDoctrineExtensionsBundle) - This bundle provides integration for DoctrineExtensions.
 * [VichGeographicalBundle](https://github.com/dustin10/VichGeographicalBundle) - A bundle which provides geographical features for ORM and ODM entities and object oriented javascript maps rendering.
 * [WizadDoctrineDocBundle](https://github.com/wpottier/WizadDoctrineDocBundle) - Allows you to generate a decent documentation for your doctrine model schema.

## Validation

 * [dms-filter-bundle](https://github.com/rdohms/dms-filter-bundle) - Provides a FilterService to allow users to implement input filtering in entities using Annotations.
 * [PasswordStrengthBundle](https://github.com/jbafford/PasswordStrengthBundle) - Validator for ensuring strong passwords.
 * [vatin-bundle](https://github.com/ddeboer/vatin-bundle) - A Symfony2 bundle for the VATIN library (validate VAT identification numbers).

## Forms

 * [CaptchaBundle](https://github.com/Gregwar/CaptchaBundle) - Bundle implementing a "captcha" form type.
 * [CraueFormFlowBundle](https://github.com/craue/CraueFormFlowBundle) - Multi-step forms.
 * [FilterFormBundle](https://github.com/IDCI-Consulting/FilterFormBundle) - Filter form bundle.
 * [FormBundle](https://github.com/Gregwar/FormBundle) - Provides the "entity_id" type.
 * [InfiniteFormBundle](https://github.com/infinite-networks/InfiniteFormBundle) - A collection of useful form types and extensions.
 * [IvoryOrderedFormBundle](https://github.com/egeloen/IvoryOrderedFormBundle) - Provides a form ordering support.
 * [LexikFormFilterBundle](https://github.com/lexik/LexikFormFilterBundle) - Lexik Form Filter bundle.

## Service Container

 * [JMSDiExtraBundle](http://jmsyst.com/bundles/JMSDiExtraBundle) - Provides Advanced Dependency Injection Features.
 * [PHP-DI](http://php-di.org) - The dependency injection container for humans.
 * [KutnyAutowiringBundle](https://github.com/kutny/autowiring-bundle) - a bundle providing autowiring for service arguments.

## Development

 * [JMSDebuggingBundle](http://jmsyst.com/bundles/JMSDebuggingBundle) - Provides advanced debugging tools.
 * [LadybugBundle](https://github.com/raulfraile/LadybugBundle) - The Simple and Extensible PHP Dumper
 * [LiipCodeBundle](https://github.com/liip/LiipCodeBundle) - A set of Symfony2 console commands to help developers deal with the various ways of identifying classes, templates, bundles, services, etc.
 * [ListenersDebugCommandBundle](https://github.com/egulias/ListenersDebugCommandBundle) - A console command to debug listeners.
 * [ParamConverterBundle](https://github.com/jakzal/ParamConverterBundle) - This bundle provides additional param converters for Symfony.
 * [PsyshBundle](https://github.com/theofidry/PsyshBundle) - Provides an enhanced PHP interactive shell with a Symfony context.
 * [PUGXGeneratorBundle](https://github.com/PUGX/PUGXGeneratorBundle) - An enhancement of SensioGeneratorBundle.
 * [SandboxBundle](https://github.com/danrevah/SandboxBundle) - Overriding controller logic & response in a Sandbox environment.
 * [TagDebugCommandBundle](https://github.com/egulias/TagDebugCommandBundle) - Integrate TagDebug library for inspecting and debugging tags
 * [TwigReflectionBundle](https://github.com/arnaud-lb/TwigReflectionBundle) - Displays what's in Twig.
 * [WebfactoryExceptionsBundle](https://github.com/webfactory/exceptions-bundle) - Easily develop custom, user-friendly error pages.
 * [WebProfilerExtraBundle](https://github.com/Elao/WebProfilerExtraBundle) - Adding routing, container, assetic & twig information in the web profiler.
 * [XhprofBundle](https://github.com/jonaswouters/XhprofBundle) - XHProf bundle.

## Assets Management

 * [assetic-extra-bundle](https://github.com/alexandresalome/assetic-extra-bundle) - Asset Directory filter for Assetic.
 * [AsseticMinifierBundle](https://github.com/Djeg/AsseticMinifierBundle) - An assetic minifier in pure PHP for CSS and JS files.
 * [FkrCssURLRewriteBundle](https://github.com/fkrauthan/FkrCssURLRewriteBundle) - A small assetic filter to fix all url paths at css documents to correct urls.
 * [IgorwFileServeBundle](https://github.com/igorw/IgorwFileServeBundle) - Bundle for serving protected files.
 * [JmikolaJsAssetsHelperBundle](https://github.com/jmikola/JmikolaJsAssetsHelperBundle) - Exposes the AssetsHelper service from Symfony2's templating component to JavaScript, allowing relative or absolute asset URI's to be generated client-side.
 * [KachkaevAssetsVersionBundle](https://github.com/kachkaev/KachkaevAssetsVersionBundle) - Automates the process of updating assets version.
 * [SalvaJshrinkBundle](https://github.com/nibsirahsieu/SalvaJshrinkBundle) - This bundle integrate jshrink library as Assetic filter and twig extension.
 * [SpritesBundle](https://github.com/pminnieur/SpritesBundle) - Bundle for the Sprites library.
 * [ZakharovviHumansTxtBundle](https://github.com/zakharovvi/ZakharovviHumansTxtBundle) - Generate humans.txt file from git repository.

## Queues

 * [GearmanBundle](http://gearmanbundle.readthedocs.org/en/latest/) - A bundle intended to provide an easy way to support developers who need to use job queues.
 * [JMSJobQueueBundle](http://jmsyst.com/bundles/JMSJobQueueBundle) - Allows to schedule console commands as jobs.
 * [LeezyPheanstalkBundle](https://github.com/armetiz/LeezyPheanstalkBundle) - Bundle for Pheanstalk, PHP client for beanstalkd queue.
 * [qpush-bundle](http://qpush-bundle.readthedocs.org/en/latest/) - The QPush Bundle relies on the Push Queue model of Message Queues to provide asynchronous processing in your application.
 * [RabbitMqBundle](https://github.com/videlalvaro/RabbitMqBundle) - RabbitMQ bundle.

## Internationalization

 * [JMSI18nRoutingBundle](http://jmsyst.com/bundles/JMSI18nRoutingBundle) - Bundle for multilingual websites to support international routes.
 * [JMSTranslationBundle](http://jmsyst.com/bundles/JMSTranslationBundle) - Translate your website with ease - extract messages & translate them via a web-based UI.
 * [LuneticsLocaleBundle](https://github.com/lunetics/LocaleBundle) - Guess the visitor’s locale from different parameters.
 * [TimezoneBundle](https://github.com/lunetics/TimezoneBundle) - Serverside Timezone detection

## Payments Management

 * [CartBundle](https://github.com/leaphly/CartBundle) - High quality cart for developers.
 * [JMSPaymentCoreBundle](http://jmsyst.com/bundles/JMSPaymentCoreBundle) - This bundle provides the foundation for various payment plugins.
 * [JMSPaymentPaypalBundle](https://github.com/schmittjoh/JMSPaymentPaypalBundle) - Payment Bundle providing access to the PayPal API.
 * [PayumBundle](https://github.com/Payum/PayumBundle) - Rich payment solutions for symfony2. Paypal, Stripe, Payex, Authorize.NET, Be2bill, Klarna, recurring paymens, instant notifications and many more

## Monitoring

 * [SoclozMonitoringBundle](https://github.com/SoCloz/SoclozMonitoringBundle) - A monitoring bundle for production servers

## Administration

 * [AdmingeneratorGeneratorBundle](https://github.com/symfony2admingenerator/AdmingeneratorGeneratorBundle) - Admingenerator for Symfony2, parse generator.yml files to build classes
 * [EasyAdminBundle](https://github.com/javiereguiluz/EasyAdminBundle) - Simple admin generator for Symfony applications
 * [SonataAdminBundle](https://github.com/sonata-project/SonataAdminBundle) - AdminBundle - The missing Symfony2 Admin Generator

## Miscellaneous

 * [AnhTaggableBundle](https://github.com/hilobok/AnhTaggableBundle) - Bundle provides integration of doctrine-extensions-taggable, adds form types for editing tag and tagging.
 * [APYBreadcrumbTrailBundle](https://github.com/Abhoryo/APYBreadcrumbTrailBundle) - This bundle provides annotations and PHP methods to generate a breacrumb trail.
 * [APYDataGridBundle](https://github.com/Abhoryo/APYDataGridBundle) - Datagrid Bundle.
 * [BazingaFakerBundle](https://github.com/willdurand/BazingaFakerBundle) - Put the awesome Faker library into the Symfony2 DIC and populate your database with fake data.
 * [BazingaGeocoderBundle](https://github.com/geocoder-php/BazingaGeocoderBundle) - Integration of the Geocoder library.
 * [BCCMyrrixBundle](https://github.com/michelsalib/BCCMyrrixBundle) - Myrrix is a recommendation engine built on Apache Mahout libraries.
 * [BGBarcodeBundle](https://github.com/paterik/BGBarcodeBundle) - Bundle for barcode rendering using our barcode generator base library.
 * [BlogBundle](https://github.com/stfalcon/BlogBundle) - Simple blog module.
 * [BreadcrumbsBundle](https://github.com/whiteoctober/BreadcrumbsBundle) - A small breadcrumbs bundle.
 * [BrowscapBundle](https://github.com/browscap/BrowscapBundle) - Bundle to access the browscap information.
 * [CacheToolBundle](https://github.com/gordalina/CacheToolBundle) - Bundle to integrate cachetool library in Symfony2 (Clear acp/opcache from the command line)
 * [CarbonBundle](https://github.com/lightsuner/CarbonBundle) - This bundle provides an opportunity to convert Request data into Carbon objects.
 * [CheckBundles](https://github.com/wjzijderveld/CheckBundles) - Checks installed but not activated in AppKernel bundles.
 * [CloudBackupBundle](https://github.com/dizda/CloudBackupBundle) - Be able to backup your database(s) and upload it to the cloud.
 * [ConsoleBundle](https://github.com/CoreSphere/ConsoleBundle) - Commandline interface in browser.
 * [ControllerExtraBundle](https://github.com/mmoreram/ControllerExtraBundle) - Controller extras bundle.
 * [EmbedlyBundle](https://github.com/EmanueleMinotto/EmbedlyBundle) - Bundle for the embed.ly library.
 * [EasyAuditBundle](http://xiidea.github.io/EasyAuditBundle/) - This bundle provides audit logging for your application - works with Doctrine2 entities and allows logging selective events.
 * [FeatureToggleBundle](https://github.com/marekkalnik/FeatureToggleBundle) - Configure your feature toggling in Symfony2 by adding some simple tags to twig and extending it's configuration.
 * [ffmpeg-bundle](https://github.com/pulse00/ffmpeg-bundle) - This bundle provides a simple wrapper for the PHP_FFmpeg library, exposing the library as a Symfony service.
 * [FlorianvSwapBundle](https://github.com/florianv/FlorianvSwapBundle) - This Bundle integrates the Swap library.
 * [godfather](https://github.com/PUGX/godfather) - A library for the strategy pattern in PHP.
 * [GoogleBundle](https://github.com/antimattr/GoogleBundle) - Bundle for Google Analytics.
 * [guzzle-bundle](https://github.com/misd-service-development/guzzle-bundle) - Integrates Guzzle.
 * [highcharts-bundle](https://github.com/misd-service-development/highcharts-bundle) - Integrates PHP Highcharts.
 * [HTMLPurifierBundle](https://github.com/arnaud-lb/HTMLPurifierBundle) - HTML Purifier is a standards-compliant HTML filter library written in PHP.
 * [IbrowsWizardAnnotationBundle](https://github.com/ibrows/IbrowsWizardAnnotationBundle) - Give's a Symfony2 controller a simple wizard/workflow with annotations.
 * [KayueEssenceBundle](https://github.com/kayue/KayueEssenceBundle) - This bundle integrates the Essence library (an oEmbed library) into Symfony 2.
 * [KitpagesDataGridBundle](https://github.com/kitpages/KitpagesDataGridBundle) - This bundle provides a simple datagrid bundle.
 * [KnpMarkdownBundle](https://github.com/KnpLabs/KnpMarkdownBundle) - Wrapper for PHP markdown.
 * [KnpSnappyBundle](https://github.com/KnpLabs/KnpSnappyBundle) - Easily create PDF and images by converting html using webkit.
 * [LiipUrlAutoConverterBundle](https://github.com/liip/LiipUrlAutoConverterBundle) - Add a Twig Extension for templates with a new filter for automatically converting urls and emails in a string to html links.
 * [metrics](https://github.com/beberlei/metrics) - Simple library that abstracts different metrics collectors.
 * [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) - Mobile_Detect is a lightweight PHP class for detecting mobile devices (including tablets).
 * [MobileDetectBundle](https://github.com/suncat2000/MobileDetectBundle) - Bundle for detect mobile devices, manage mobile view and redirect to the mobile and tablet version.
 * [MultiParamBundle](https://github.com/jaytaph/MultiParamBundle) - MultiParam Annotation Bundle.
 * [OneupUploaderBundle](https://github.com/1up-lab/OneupUploaderBundle) - Provides server implementations for several multi file uploader.
 * [phone-number-bundle](https://github.com/misd-service-development/phone-number-bundle) - Integrates libphonenumber.
 * [prezent-grid-bundle](https://github.com/Prezent/prezent-grid-bundle) - Integrate the prezent/grid library in Symfony2.
 * [rss-atom-bundle](https://github.com/alexdebril/rss-atom-bundle) - RSS and Atom Bundle.
 * [Search-SphinxsearchBundle](https://github.com/timewasted/Search-SphinxsearchBundle) - Sphinx search bundle.
 * [SettingsBundle](https://github.com/dmishh/SettingsBundle) - Database centric configuration management. Global and per-user settings supported.
 * [shorturl-bundle](https://github.com/fabstei/shorturl-bundle) - Provides short URLs for your project.
 * [sphinx-realtime-bundle](https://github.com/camdram/sphinx-realtime-bundle) - A bundle which automatically syncs Doctrine entities to a Sphinx real-time index.
 * [SphinxsearchBundle](https://github.com/IAkumaI/SphinxsearchBundle) - Provide to use Sphinx search.
 * [StringGeneratorBundle](https://github.com/vivait/StringGeneratorBundle) - This bundle allows you to automatically generate a unique random string on an entity property, useful for creating keys.
 * [TbbcCacheBundle](https://github.com/TheBigBrainsCompany/TbbcCacheBundle) - Cache abstraction bundle.
 * [TemplatedUriBundle](https://github.com/hautelook/TemplatedUriBundle) - Expose the hautelook/TemplatedUriRouter.
 * [timeline-bundle](https://github.com/stephpy/timeline-bundle) - Symfony2 bundle to make timeline
 * [TimelineBundle](https://github.com/stephpy/TimelineBundle) - Integrates timeline.
 * [TransmissionBundle](https://github.com/chellem/TransmissionBundle) - Bundle for Transmission API client.
 * [versioning-bundle](https://github.com/shivas/versioning-bundle) - Simple way to version (semantic versioning 2.0.0).
 * [WhiteOctoberPagerfantaBundle](https://github.com/whiteoctober/WhiteOctoberPagerfantaBundle) - Bundle to use Pagerfanta.
 * [WidopFrameworkExtraBundle](https://github.com/widop/WidopFrameworkExtraBundle) - Adds annotation configuration for Controller classes.
 * [WozbeRedirectBundle](https://github.com/wozbe/WozbeRedirectBundle) - A short bundle to manage many domains.

## Third Party APIs
 * [GordalinaMixpanelBundle](https://github.com/gordalina/GordalinaMixpanelBundle) - Mixpanel integration in Symfony2
 * [SwarrotBundle](https://github.com/swarrot/SwarrotBundle) - A bundle for swarrot integration.

## Reading

 * [Assets Cache Busting in Symfony](http://elnur.pro/assets-cache-busting-in-symfony/)
 * [High Performance Websites with Symfony2](http://slides.seld.be/?file=2011-10-20+High+Performance+Websites+with+Symfony2.html)
 * [Rationally boost your symfony2 application with caching tips and monitoring](http://www.slideshare.net/liuggio/rationally-boost-your-symfony2-application-with-caching-tips-and-monitoring)
 * [Symfony - project tamed](http://clearcode.cc/2014/03/symfony-project/)
 * [Symfony2 cheat sheet](http://www.symfony2cheatsheet.com/)

## Distributions

* [KnpLabs RAD Edition](https://github.com/KnpLabs/rad-edition)
* [Kunstmaan Bundles Standard Edition](https://github.com/Kunstmaan/KunstmaanBundlesStandardEdition)
* [Liip RAD Edition](https://github.com/liip/symfony-rad-edition)
* [Symfony Biga Edition](https://github.com/JoshuaEstes/symfony-biga-edition)
* [Symfony Bootstrap Edition](https://github.com/phiamo/symfony-bootstrap)
* [Symfony CMF Standard Edition](https://github.com/symfony-cmf/standard-edition)
* [Symfony EmberJs Edition](https://github.com/ucsf-ckm/symfony-emberjs-edition)
* [Symfony Emptier Edition](https://github.com/gnugat/sf2-emptier)
* [Symfony Empty Edition](https://github.com/gnugat/symfony-empty)
* [Symfony Micro Edition](https://github.com/magnusnordlander/symfony-micro)
* [Symfony Nerdery Edition](https://github.com/thenerdery/symfony-standard)
* [Symfony REST Edition](https://github.com/gimler/symfony-rest-edition)
* [Symfony Sonata Edition](https://github.com/jmather/symfony-sonata-distribution)
* [Symfony Standard Edition](https://github.com/symfony/symfony-standard)

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Emanuele Minotto](http://emanueleminotto.github.io) has waived all copyright and related or neighboring rights to this work.
