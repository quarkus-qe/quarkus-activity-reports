Weekly Digest for quarkusio/quarkus (30 August, 2019 - 6 September, 2019)



 - - - 

# ISSUES

Last week 119 issues were created.

Of these, 61 issues have been closed and 58 issues are still open.

## OPEN ISSUES

:green_heart: #3898 [gradlew quarkusDev -> NullPointerException on startup](https://github.com/quarkusio/quarkus/issues/3898), by [jrevault](https://github.com/jrevault)

:green_heart: #3897 [Update to Maven 3.6.2](https://github.com/quarkusio/quarkus/pull/3897), by [gastaldi](https://github.com/gastaldi)

:green_heart: #3896 [Split Vert.x and Vert.x web in two separate extensions](https://github.com/quarkusio/quarkus/pull/3896), by [stuartwdouglas](https://github.com/stuartwdouglas)

:green_heart: #3895 [Native s2i binary image fails to run SSL-enabled apps](https://github.com/quarkusio/quarkus/issues/3895), by [jamesfalkner](https://github.com/jamesfalkner)

:green_heart: #3894 [#3120 fix hibernate envers native execution](https://github.com/quarkusio/quarkus/pull/3894), by [dcdh](https://github.com/dcdh)

:green_heart: #3893 [Make RestAssured aware of configured servlet context path](https://github.com/quarkusio/quarkus/pull/3893), by [gwenneg](https://github.com/gwenneg)

:green_heart: #3892 [Remove duplicate vertx-mysql-client dependency from BOM](https://github.com/quarkusio/quarkus/pull/3892), by [gwenneg](https://github.com/gwenneg)

:green_heart: #3890 [Offer a conversion table between Spring Boot annotations and Quarkus annotations](https://github.com/quarkusio/quarkus/issues/3890), by [emmanuelbernard](https://github.com/emmanuelbernard)

:green_heart: #3889 [java.security.cert.CertificateException when connecting to SSL-enabled MongoDB from native app](https://github.com/quarkusio/quarkus/issues/3889), by [jamesfalkner](https://github.com/jamesfalkner)

:green_heart: #3888 [Injecting @ConfigProperty(name="quarkus.servlet.context-path") does not work in native mode](https://github.com/quarkusio/quarkus/issues/3888), by [jglick](https://github.com/jglick)

:green_heart: #3887 [Add support for Asciidoc in configuration reference documentation](https://github.com/quarkusio/quarkus/pull/3887), by [gsmet](https://github.com/gsmet)

:green_heart: #3886 [Support deployment and hot deployment of additional web content beyond src/main/resources/META-INF/resources](https://github.com/quarkusio/quarkus/issues/3886), by [aaronanderson](https://github.com/aaronanderson)

:green_heart: #3884 [skip TestScopeManager.setup()/tearDown() for a substrate test](https://github.com/quarkusio/quarkus/issues/3884), by [vsevel](https://github.com/vsevel)

:green_heart: #3883 [Make the RegisterForReflection annotation more flexible for Native](https://github.com/quarkusio/quarkus/issues/3883), by [lbernardomaia](https://github.com/lbernardomaia)

:green_heart: #3881 [Memory usage increase with the new network stack](https://github.com/quarkusio/quarkus/issues/3881), by [cescoffier](https://github.com/cescoffier)

:green_heart: #3879 [Autocompile new projects before starting dev mode](https://github.com/quarkusio/quarkus/pull/3879), by [evanchooly](https://github.com/evanchooly)

:green_heart: #3878 [Add support for @TransactionalScoped into narayana extension](https://github.com/quarkusio/quarkus/issues/3878), by [manovotn](https://github.com/manovotn)

:green_heart: #3876 [RestAssured unaware of quarkus.servlet.context-path, revisited](https://github.com/quarkusio/quarkus/issues/3876), by [jglick](https://github.com/jglick)

:green_heart: #3874 [exclude org.osgi.annotation.versioning](https://github.com/quarkusio/quarkus/pull/3874), by [michalszynkiewicz](https://github.com/michalszynkiewicz)

:green_heart: #3873 [Fixes after going through getting started guide](https://github.com/quarkusio/quarkus/pull/3873), by [maxandersen](https://github.com/maxandersen)

:green_heart: #3871 [RestEasy extension no longer picks up Resource implementations with a corresponding interface](https://github.com/quarkusio/quarkus/issues/3871), by [garyttierney](https://github.com/garyttierney)

:green_heart: #3870 [PanacheQuery.range()](https://github.com/quarkusio/quarkus/issues/3870), by [loicmathieu](https://github.com/loicmathieu)

:green_heart: #3869 [NPE in ArcTestRequestScopeProvider.setup() in native mode Fixes #3790](https://github.com/quarkusio/quarkus/pull/3869), by [vsevel](https://github.com/vsevel)

:green_heart: #3867 [Improve Quarkus testing framework](https://github.com/quarkusio/quarkus/issues/3867), by [teoincontatto](https://github.com/teoincontatto)

:green_heart: #3866 [Remove the JaxbEnabledBuildItem from the resteasy-server-common exten…](https://github.com/quarkusio/quarkus/pull/3866), by [gnodet](https://github.com/gnodet)

:green_heart: #3864 [DynamoDB configurations update](https://github.com/quarkusio/quarkus/pull/3864), by [marcinczeczko](https://github.com/marcinczeczko)

:green_heart: #3862 [mvn quarkus:remote-dev does not work when quarkus.servlet.context-path specified](https://github.com/quarkusio/quarkus/issues/3862), by [jglick](https://github.com/jglick)

:green_heart: #3861 [quarkus-reactive-pg-client extension fails to pull pg-client-deployment dependency during build](https://github.com/quarkusio/quarkus/issues/3861), by [tsfullman](https://github.com/tsfullman)

:green_heart: #3860 [Provides an opt-in for jaxb support in resteasy-server-common extension](https://github.com/quarkusio/quarkus/issues/3860), by [gnodet](https://github.com/gnodet)

:green_heart: #3859 [Native testing is broken on non linux platforms](https://github.com/quarkusio/quarkus/issues/3859), by [gnodet](https://github.com/gnodet)

:green_heart: #3856 [RESTEasy extension should throw a build error if consuming or producing JSON without any JSON body writer/reader](https://github.com/quarkusio/quarkus/issues/3856), by [gsmet](https://github.com/gsmet)

:green_heart: #3855 [Gradle and config source](https://github.com/quarkusio/quarkus/issues/3855), by [jrevault](https://github.com/jrevault)

:green_heart: #3854 [More fixes to the error pages](https://github.com/quarkusio/quarkus/pull/3854), by [gsmet](https://github.com/gsmet)

:green_heart: #3852 [404 page does not list swagger-ui](https://github.com/quarkusio/quarkus/issues/3852), by [emmanuelbernard](https://github.com/emmanuelbernard)

:green_heart: #3851 [Improvements for 404](https://github.com/quarkusio/quarkus/issues/3851), by [emmanuelbernard](https://github.com/emmanuelbernard)

:green_heart: #3842 [Container not running error when playing with dev mode on a simple app](https://github.com/quarkusio/quarkus/issues/3842), by [gsmet](https://github.com/gsmet)

:green_heart: #3836 [Add an option for create-extension mojo to create an itest module](https://github.com/quarkusio/quarkus/pull/3836), by [ppalaga](https://github.com/ppalaga)

:green_heart: #3834 [Defining quarkus.version on command line fails the tests](https://github.com/quarkusio/quarkus/issues/3834), by [rsvoboda](https://github.com/rsvoboda)

:green_heart: #3833 [ArtemisTestResource available](https://github.com/quarkusio/quarkus/issues/3833), by [lordofthejars](https://github.com/lordofthejars)

:green_heart: #3832 [Infinispan Embedded Extension](https://github.com/quarkusio/quarkus/pull/3832), by [wburns](https://github.com/wburns)

:green_heart: #3828 [Native image: Discrepancy between default https/http protocol and the actual used one](https://github.com/quarkusio/quarkus/issues/3828), by [Karm](https://github.com/Karm)

:green_heart: #3823 [Split Vert.x and Vert.x web in two separate extensions](https://github.com/quarkusio/quarkus/pull/3823), by [gsmet](https://github.com/gsmet)

:green_heart: #3822 [Update to latest SmallRye OpenAPI](https://github.com/quarkusio/quarkus/pull/3822), by [kenfinnigan](https://github.com/kenfinnigan)

:green_heart: #3817 [cryptic error when providing import.sql file without ; at the end of each line](https://github.com/quarkusio/quarkus/issues/3817), by [emmanuelbernard](https://github.com/emmanuelbernard)

:green_heart: #3813 [Kotlin project fails to include JAXP classes provided by JDK](https://github.com/quarkusio/quarkus/issues/3813), by [boonyasukd](https://github.com/boonyasukd)

:green_heart: #3811 [Initializing the default config at runtime](https://github.com/quarkusio/quarkus/pull/3811), by [sberyozkin](https://github.com/sberyozkin)

:green_heart: #3806 [Propertie amqp-host does not work for reactive-messaging-amqp](https://github.com/quarkusio/quarkus/issues/3806), by [BiggA94](https://github.com/BiggA94)

:green_heart: #3803 [Improve generated configuration documentation (round 2)](https://github.com/quarkusio/quarkus/issues/3803), by [emmanuelbernard](https://github.com/emmanuelbernard)

:green_heart: #3802 [Move the static file support to Vert.x](https://github.com/quarkusio/quarkus/issues/3802), by [cescoffier](https://github.com/cescoffier)

:green_heart: #3797 [add graal vm to build machines](https://github.com/quarkusio/quarkus/issues/3797), by [vsevel](https://github.com/vsevel)

:green_heart: #3796 [add docker to windows build machine in quarkus-ci](https://github.com/quarkusio/quarkus/issues/3796), by [vsevel](https://github.com/vsevel)

:green_heart: #3792 [Added  Access Log Configuration Sample Documentation](https://github.com/quarkusio/quarkus/pull/3792), by [masini](https://github.com/masini)

:green_heart: #3790 [NPE in ArcTestRequestScopeProvider.setup() in native mode with dependency on deployment test jar](https://github.com/quarkusio/quarkus/issues/3790), by [vsevel](https://github.com/vsevel)

:green_heart: #3787 [Unable to run test using `mvn clean test` on main application when Flyway is embedded in an external jar.](https://github.com/quarkusio/quarkus/issues/3787), by [dcdh](https://github.com/dcdh)

:green_heart: #3786 [Tests fails if quarkus project has been created with -Dpath=/ system setting passed to maven plugin](https://github.com/quarkusio/quarkus/issues/3786), by [daggerok](https://github.com/daggerok)

:green_heart: #3783 [add scheduler configuration and add support for clustered jobs](https://github.com/quarkusio/quarkus/pull/3783), by [machi1990](https://github.com/machi1990)

:green_heart: #3782 [Performance on MacBook pro](https://github.com/quarkusio/quarkus/issues/3782), by [FreifeldRoyi](https://github.com/FreifeldRoyi)

:green_heart: #3781 [Register JAX-RS classes by default](https://github.com/quarkusio/quarkus/issues/3781), by [FreifeldRoyi](https://github.com/FreifeldRoyi)

## CLOSED ISSUES

:heart: #3891 [Put the same style in the reactive drivers table](https://github.com/quarkusio/quarkus/pull/3891), by [lordofthejars](https://github.com/lordofthejars)

:heart: #3885 [Set timeout for each native build to detect unexpected duration increase](https://github.com/quarkusio/quarkus/pull/3885), by [cescoffier](https://github.com/cescoffier)

:heart: #3882 [Fix the isInIOThread detection](https://github.com/quarkusio/quarkus/pull/3882), by [cescoffier](https://github.com/cescoffier)

:heart: #3880 [Add support for Spring's @Value in a constructor](https://github.com/quarkusio/quarkus/pull/3880), by [geoand](https://github.com/geoand)

:heart: #3877 [More config doc improvements](https://github.com/quarkusio/quarkus/pull/3877), by [gsmet](https://github.com/gsmet)

:heart: #3875 [Add missing spring-web feature](https://github.com/quarkusio/quarkus/pull/3875), by [geoand](https://github.com/geoand)

:heart: #3872 [fix(swagger-ui): throw an error when "/" is set as swagger-ui path](https://github.com/quarkusio/quarkus/pull/3872), by [machi1990](https://github.com/machi1990)

:heart: #3868 [Intermitent failure on ConfigurationSetup#initializeConfiguration during livereload](https://github.com/quarkusio/quarkus/issues/3868), by [loicmathieu](https://github.com/loicmathieu)

:heart: #3865 [Don't append @Dependent to REST endpoints](https://github.com/quarkusio/quarkus/pull/3865), by [jmartisk](https://github.com/jmartisk)

:heart: #3863 [dev mode error with multiple application properties profiles](https://github.com/quarkusio/quarkus/issues/3863), by [jeremyrdavis](https://github.com/jeremyrdavis)

:heart: #3858 [fix: file not found exception during doc generation](https://github.com/quarkusio/quarkus/pull/3858), by [machi1990](https://github.com/machi1990)

:heart: #3857 [Openapi not working when quarkus.swagger-ui.path is "/"](https://github.com/quarkusio/quarkus/issues/3857), by [lbernardomaia](https://github.com/lbernardomaia)

:heart: #3853 [NotFoundExceptionMapper: use proper content type variants, fix CCE](https://github.com/quarkusio/quarkus/pull/3853), by [FroMage](https://github.com/FroMage)

:heart: #3850 [Fix ClassCastException in not found error page](https://github.com/quarkusio/quarkus/pull/3850), by [stuartwdouglas](https://github.com/stuartwdouglas)

:heart: #3849 [Fixes #3844](https://github.com/quarkusio/quarkus/pull/3849), by [stuartwdouglas](https://github.com/stuartwdouglas)

:heart: #3848 [makes inclusion of generated docs optional](https://github.com/quarkusio/quarkus/pull/3848), by [machi1990](https://github.com/machi1990)

:heart: #3847 [[DO NOT MERGE] 0.21 backports for CI testing](https://github.com/quarkusio/quarkus/pull/3847), by [gsmet](https://github.com/gsmet)

:heart: #3846 [Dev mode: weird ZIP error on shutdown](https://github.com/quarkusio/quarkus/issues/3846), by [gsmet](https://github.com/gsmet)

:heart: #3845 [Fix error page layout and appearance](https://github.com/quarkusio/quarkus/pull/3845), by [gsmet](https://github.com/gsmet)

:heart: #3844 [Dev mode: several Vert.x worker threads detecting the change](https://github.com/quarkusio/quarkus/issues/3844), by [gsmet](https://github.com/gsmet)

:heart: #3843 [Fixes column number in Infinispan guide from 3 to 4.](https://github.com/quarkusio/quarkus/pull/3843), by [lordofthejars](https://github.com/lordofthejars)

:heart: #3841 [Null normal scoped producers throw IllegalProductException](https://github.com/quarkusio/quarkus/pull/3841), by [mkouba](https://github.com/mkouba)

:heart: #3840 [Bad styling for error page](https://github.com/quarkusio/quarkus/issues/3840), by [gsmet](https://github.com/gsmet)

:heart: #3839 [DynamoDB: Re-enable async support](https://github.com/quarkusio/quarkus/pull/3839), by [marcinczeczko](https://github.com/marcinczeczko)

:heart: #3838 [REST endpoint containing a @Gauge annotation will not work properly](https://github.com/quarkusio/quarkus/issues/3838), by [jmartisk](https://github.com/jmartisk)

:heart: #3837 [Fix intermittent failures in ImportSqlHotReloadScriptTestCase](https://github.com/quarkusio/quarkus/pull/3837), by [stuartwdouglas](https://github.com/stuartwdouglas)

:heart: #3835 [Fixing broken list rendering](https://github.com/quarkusio/quarkus/pull/3835), by [gunnarmorling](https://github.com/gunnarmorling)

:heart: #3831 [Normal scoped producer method that returns null value at runtime should throw IllegalProductException](https://github.com/quarkusio/quarkus/pull/3831), by [gastaldi](https://github.com/gastaldi)

:heart: #3830 [Update to latest SmallRye Metrics and Fault Tolerance](https://github.com/quarkusio/quarkus/pull/3830), by [kenfinnigan](https://github.com/kenfinnigan)

:heart: #3829 [Normal scoped producer method that returns null value at runtime should throw IllegalProductException](https://github.com/quarkusio/quarkus/issues/3829), by [mkouba](https://github.com/mkouba)

:heart: #3827 [Update to latest SmallRye OpenTracing](https://github.com/quarkusio/quarkus/pull/3827), by [kenfinnigan](https://github.com/kenfinnigan)

:heart: #3826 [Update to latest SmallRye Health](https://github.com/quarkusio/quarkus/pull/3826), by [kenfinnigan](https://github.com/kenfinnigan)

:heart: #3825 [Update to latest SmallRye JWT](https://github.com/quarkusio/quarkus/pull/3825), by [kenfinnigan](https://github.com/kenfinnigan)

:heart: #3824 [Upgrade Flyway 6.0.1](https://github.com/quarkusio/quarkus/pull/3824), by [loicmathieu](https://github.com/loicmathieu)

:heart: #3821 [Fix missing qualifiers in reactive messaging](https://github.com/quarkusio/quarkus/pull/3821), by [cescoffier](https://github.com/cescoffier)

:heart: #3820 [RESTEasy does not return the ErrorMessage when JSON is expected from the client](https://github.com/quarkusio/quarkus/issues/3820), by [emmanuelbernard](https://github.com/emmanuelbernard)

:heart: #3819 [Remove Elytron SSL dependencies](https://github.com/quarkusio/quarkus/pull/3819), by [stuartwdouglas](https://github.com/stuartwdouglas)

:heart: #3818 [Cannot  build master, Docs, asciidoctor:, datasource-guide.adoc: line 228: include file not found](https://github.com/quarkusio/quarkus/issues/3818), by [Karm](https://github.com/Karm)

:heart: #3816 [Test Keycloak in CI](https://github.com/quarkusio/quarkus/pull/3816), by [stuartwdouglas](https://github.com/stuartwdouglas)

:heart: #3815 [Drop useless Class.forName from generated Spring Data JPA repositories](https://github.com/quarkusio/quarkus/pull/3815), by [geoand](https://github.com/geoand)

:heart: #3814 [Ensure the Kubernetes extension doesn't register too much reflection for Jackson](https://github.com/quarkusio/quarkus/pull/3814), by [geoand](https://github.com/geoand)

:heart: #3812 [Upgrade narayana.version to 5.9.8.Final](https://github.com/quarkusio/quarkus/pull/3812), by [gwenneg](https://github.com/gwenneg)

:heart: #3810 [Drop jboss-invocation and start working on JDK 12+ proxy creation](https://github.com/quarkusio/quarkus/pull/3810), by [geoand](https://github.com/geoand)

:heart: #3809 [Tweak the configuration reference generation](https://github.com/quarkusio/quarkus/pull/3809), by [FroMage](https://github.com/FroMage)

:heart: #3808 [Create CODE_OF_CONDUCT.md](https://github.com/quarkusio/quarkus/pull/3808), by [gastaldi](https://github.com/gastaldi)

:heart: #3807 [Add gradle.properties to the gradle plugin project](https://github.com/quarkusio/quarkus/pull/3807), by [aloubyansky](https://github.com/aloubyansky)

:heart: #3805 [Upgrade to RESTEasy 4.3.0.Final](https://github.com/quarkusio/quarkus/pull/3805), by [asoldano](https://github.com/asoldano)

:heart: #3804 [Gradle plugin module is missing gradle.properties](https://github.com/quarkusio/quarkus/issues/3804), by [aloubyansky](https://github.com/aloubyansky)

:heart: #3801 [fix quarkus-smallrye-reactive-messaging-amqp artifactId in bom](https://github.com/quarkusio/quarkus/pull/3801), by [cescoffier](https://github.com/cescoffier)

:heart: #3800 [Rename Subclass method](https://github.com/quarkusio/quarkus/pull/3800), by [stuartwdouglas](https://github.com/stuartwdouglas)

:heart: #3799 [Add the ability to detect if a blocking op is performed in the IO thread](https://github.com/quarkusio/quarkus/pull/3799), by [stuartwdouglas](https://github.com/stuartwdouglas)

:heart: #3798 [Fix CI](https://github.com/quarkusio/quarkus/pull/3798), by [stuartwdouglas](https://github.com/stuartwdouglas)

:heart: #3795 [Native image of quickstart application has memory leak problem both native executable and docker version.](https://github.com/quarkusio/quarkus/issues/3795), by [thaweechok](https://github.com/thaweechok)

:heart: #3794 [Fix maven cache on windows](https://github.com/quarkusio/quarkus/pull/3794), by [stuartwdouglas](https://github.com/stuartwdouglas)

:heart: #3793 [#3787 handle different sources of migrations files](https://github.com/quarkusio/quarkus/pull/3793), by [dcdh](https://github.com/dcdh)

:heart: #3791 [Document Undertow HTTP Access Log Configuration](https://github.com/quarkusio/quarkus/pull/3791), by [masini](https://github.com/masini)

:heart: #3789 [TestScopeManager. tearDown() calls setup() instead of tearDown() Fixes issue #3784](https://github.com/quarkusio/quarkus/pull/3789), by [vsevel](https://github.com/vsevel)

:heart: #3788 [Add MicroProfile OpenAPI TCK](https://github.com/quarkusio/quarkus/pull/3788), by [kenfinnigan](https://github.com/kenfinnigan)

:heart: #3785 [Unable to start quarkus with spring data jpa dependencies](https://github.com/quarkusio/quarkus/issues/3785), by [naushadamin](https://github.com/naushadamin)

:heart: #3784 [TestScopeManager. tearDown() calls setup() instead of tearDown()](https://github.com/quarkusio/quarkus/issues/3784), by [vsevel](https://github.com/vsevel)

:heart: #3780 [Fix example snippet typo containing double ']'](https://github.com/quarkusio/quarkus/pull/3780), by [tarilabs](https://github.com/tarilabs)

## LIKED ISSUE

:+1: #3861 [quarkus-reactive-pg-client extension fails to pull pg-client-deployment dependency during build](https://github.com/quarkusio/quarkus/issues/3861), by [tsfullman](https://github.com/tsfullman)

It received :+1: x4, :smile: x0, :tada: x0 and :heart: x0.

## NOISY ISSUE

:speaker: #3803 [Improve generated configuration documentation (round 2)](https://github.com/quarkusio/quarkus/issues/3803), by [emmanuelbernard](https://github.com/emmanuelbernard)

It received 16 comments.



 - - - 

# PULL REQUESTS

Last week, 86 pull requests were created, updated or merged.

## OPEN PULL REQUEST

Last week, 1 pull request was opened.

:green_heart: #3894 [#3120 fix hibernate envers native execution](https://github.com/quarkusio/quarkus/pull/3894), by [dcdh](https://github.com/dcdh)

## UPDATED PULL REQUEST

Last week, 34 pull requests were updated.

:yellow_heart: #3897 [Update to Maven 3.6.2](https://github.com/quarkusio/quarkus/pull/3897), by [gastaldi](https://github.com/gastaldi)

:yellow_heart: #3896 [Split Vert.x and Vert.x web in two separate extensions](https://github.com/quarkusio/quarkus/pull/3896), by [stuartwdouglas](https://github.com/stuartwdouglas)

:yellow_heart: #3893 [Make RestAssured aware of configured servlet context path](https://github.com/quarkusio/quarkus/pull/3893), by [gwenneg](https://github.com/gwenneg)

:yellow_heart: #3892 [Remove duplicate vertx-mysql-client dependency from BOM](https://github.com/quarkusio/quarkus/pull/3892), by [gwenneg](https://github.com/gwenneg)

:yellow_heart: #3887 [Add support for Asciidoc in configuration reference documentation](https://github.com/quarkusio/quarkus/pull/3887), by [gsmet](https://github.com/gsmet)

:yellow_heart: #3879 [Autocompile new projects before starting dev mode](https://github.com/quarkusio/quarkus/pull/3879), by [evanchooly](https://github.com/evanchooly)

:yellow_heart: #3874 [exclude org.osgi.annotation.versioning](https://github.com/quarkusio/quarkus/pull/3874), by [michalszynkiewicz](https://github.com/michalszynkiewicz)

:yellow_heart: #3873 [Fixes after going through getting started guide](https://github.com/quarkusio/quarkus/pull/3873), by [maxandersen](https://github.com/maxandersen)

:yellow_heart: #3869 [NPE in ArcTestRequestScopeProvider.setup() in native mode Fixes #3790](https://github.com/quarkusio/quarkus/pull/3869), by [vsevel](https://github.com/vsevel)

:yellow_heart: #3866 [Remove the JaxbEnabledBuildItem from the resteasy-server-common exten…](https://github.com/quarkusio/quarkus/pull/3866), by [gnodet](https://github.com/gnodet)

:yellow_heart: #3864 [DynamoDB configurations update](https://github.com/quarkusio/quarkus/pull/3864), by [marcinczeczko](https://github.com/marcinczeczko)

:yellow_heart: #3854 [More fixes to the error pages](https://github.com/quarkusio/quarkus/pull/3854), by [gsmet](https://github.com/gsmet)

:yellow_heart: #3836 [Add an option for create-extension mojo to create an itest module](https://github.com/quarkusio/quarkus/pull/3836), by [ppalaga](https://github.com/ppalaga)

:yellow_heart: #3832 [Infinispan Embedded Extension](https://github.com/quarkusio/quarkus/pull/3832), by [wburns](https://github.com/wburns)

:yellow_heart: #3823 [Split Vert.x and Vert.x web in two separate extensions](https://github.com/quarkusio/quarkus/pull/3823), by [gsmet](https://github.com/gsmet)

:yellow_heart: #3822 [Update to latest SmallRye OpenAPI](https://github.com/quarkusio/quarkus/pull/3822), by [kenfinnigan](https://github.com/kenfinnigan)

:yellow_heart: #3811 [Initializing the default config at runtime](https://github.com/quarkusio/quarkus/pull/3811), by [sberyozkin](https://github.com/sberyozkin)

:yellow_heart: #3792 [Added  Access Log Configuration Sample Documentation](https://github.com/quarkusio/quarkus/pull/3792), by [masini](https://github.com/masini)

:yellow_heart: #3783 [add scheduler configuration and add support for clustered jobs](https://github.com/quarkusio/quarkus/pull/3783), by [machi1990](https://github.com/machi1990)

:yellow_heart: #3778 [Fixes for JAX-RS and reactive return types](https://github.com/quarkusio/quarkus/pull/3778), by [stuartwdouglas](https://github.com/stuartwdouglas)

:yellow_heart: #3764 [Bring in new quarkus-security API](https://github.com/quarkusio/quarkus/pull/3764), by [stuartwdouglas](https://github.com/stuartwdouglas)

:yellow_heart: #3754 [Prototype of a build-parent split into a parent for apps, extensions and internal build](https://github.com/quarkusio/quarkus/pull/3754), by [aloubyansky](https://github.com/aloubyansky)

:yellow_heart: #3671 [Provides extension health via builditem](https://github.com/quarkusio/quarkus/pull/3671), by [loicmathieu](https://github.com/loicmathieu)

:yellow_heart: #3654 [Elytron-security support for Database Identity Store](https://github.com/quarkusio/quarkus/pull/3654), by [danielpetisme](https://github.com/danielpetisme)

:yellow_heart: #3650 [Extension: MongoDB with Panache](https://github.com/quarkusio/quarkus/pull/3650), by [loicmathieu](https://github.com/loicmathieu)

:yellow_heart: #3631 [Resteasy without servlet/undertow](https://github.com/quarkusio/quarkus/pull/3631), by [patriot1burke](https://github.com/patriot1burke)

:yellow_heart: #3559 [Circular dependencies](https://github.com/quarkusio/quarkus/pull/3559), by [mthmulders](https://github.com/mthmulders)

:yellow_heart: #3555 [Start using Gradle Tooling API](https://github.com/quarkusio/quarkus/pull/3555), by [Dufgui](https://github.com/Dufgui)

:yellow_heart: #3553 [Introduce the ability to configure Jsonb and generate serializers for JAX-RS return types](https://github.com/quarkusio/quarkus/pull/3553), by [geoand](https://github.com/geoand)

:yellow_heart: #3404 [Add http servers max body size and max headers size limits](https://github.com/quarkusio/quarkus/pull/3404), by [machi1990](https://github.com/machi1990)

:yellow_heart: #3398 [Change default value of `sql-load-script` to `no-file` in PROD mode](https://github.com/quarkusio/quarkus/pull/3398), by [gwenneg](https://github.com/gwenneg)

:yellow_heart: #3338 [Build jar in Augment phase](https://github.com/quarkusio/quarkus/pull/3338), by [stuartwdouglas](https://github.com/stuartwdouglas)

:yellow_heart: #2952 [Support for weak build item production and virtual build items](https://github.com/quarkusio/quarkus/pull/2952), by [dmlloyd](https://github.com/dmlloyd)

:yellow_heart: #2897 [vault](https://github.com/quarkusio/quarkus/pull/2897), by [vsevel](https://github.com/vsevel)

## MERGED PULL REQUEST

Last week, 51 pull requests were merged.

:purple_heart: #3891 [Put the same style in the reactive drivers table](https://github.com/quarkusio/quarkus/pull/3891), by [lordofthejars](https://github.com/lordofthejars)

:purple_heart: #3885 [Set timeout for each native build to detect unexpected duration increase](https://github.com/quarkusio/quarkus/pull/3885), by [cescoffier](https://github.com/cescoffier)

:purple_heart: #3882 [Fix the isInIOThread detection](https://github.com/quarkusio/quarkus/pull/3882), by [cescoffier](https://github.com/cescoffier)

:purple_heart: #3880 [Add support for Spring's @Value in a constructor](https://github.com/quarkusio/quarkus/pull/3880), by [geoand](https://github.com/geoand)

:purple_heart: #3877 [More config doc improvements](https://github.com/quarkusio/quarkus/pull/3877), by [gsmet](https://github.com/gsmet)

:purple_heart: #3875 [Add missing spring-web feature](https://github.com/quarkusio/quarkus/pull/3875), by [geoand](https://github.com/geoand)

:purple_heart: #3872 [fix(swagger-ui): throw an error when "/" is set as swagger-ui path](https://github.com/quarkusio/quarkus/pull/3872), by [machi1990](https://github.com/machi1990)

:purple_heart: #3865 [Don't append @Dependent to REST endpoints](https://github.com/quarkusio/quarkus/pull/3865), by [jmartisk](https://github.com/jmartisk)

:purple_heart: #3858 [fix: file not found exception during doc generation](https://github.com/quarkusio/quarkus/pull/3858), by [machi1990](https://github.com/machi1990)

:purple_heart: #3849 [Fixes #3844](https://github.com/quarkusio/quarkus/pull/3849), by [stuartwdouglas](https://github.com/stuartwdouglas)

:purple_heart: #3848 [makes inclusion of generated docs optional](https://github.com/quarkusio/quarkus/pull/3848), by [machi1990](https://github.com/machi1990)

:purple_heart: #3847 [[DO NOT MERGE] 0.21 backports for CI testing](https://github.com/quarkusio/quarkus/pull/3847), by [gsmet](https://github.com/gsmet)

:purple_heart: #3845 [Fix error page layout and appearance](https://github.com/quarkusio/quarkus/pull/3845), by [gsmet](https://github.com/gsmet)

:purple_heart: #3843 [Fixes column number in Infinispan guide from 3 to 4.](https://github.com/quarkusio/quarkus/pull/3843), by [lordofthejars](https://github.com/lordofthejars)

:purple_heart: #3841 [Null normal scoped producers throw IllegalProductException](https://github.com/quarkusio/quarkus/pull/3841), by [mkouba](https://github.com/mkouba)

:purple_heart: #3839 [DynamoDB: Re-enable async support](https://github.com/quarkusio/quarkus/pull/3839), by [marcinczeczko](https://github.com/marcinczeczko)

:purple_heart: #3837 [Fix intermittent failures in ImportSqlHotReloadScriptTestCase](https://github.com/quarkusio/quarkus/pull/3837), by [stuartwdouglas](https://github.com/stuartwdouglas)

:purple_heart: #3835 [Fixing broken list rendering](https://github.com/quarkusio/quarkus/pull/3835), by [gunnarmorling](https://github.com/gunnarmorling)

:purple_heart: #3830 [Update to latest SmallRye Metrics and Fault Tolerance](https://github.com/quarkusio/quarkus/pull/3830), by [kenfinnigan](https://github.com/kenfinnigan)

:purple_heart: #3827 [Update to latest SmallRye OpenTracing](https://github.com/quarkusio/quarkus/pull/3827), by [kenfinnigan](https://github.com/kenfinnigan)

:purple_heart: #3826 [Update to latest SmallRye Health](https://github.com/quarkusio/quarkus/pull/3826), by [kenfinnigan](https://github.com/kenfinnigan)

:purple_heart: #3825 [Update to latest SmallRye JWT](https://github.com/quarkusio/quarkus/pull/3825), by [kenfinnigan](https://github.com/kenfinnigan)

:purple_heart: #3824 [Upgrade Flyway 6.0.1](https://github.com/quarkusio/quarkus/pull/3824), by [loicmathieu](https://github.com/loicmathieu)

:purple_heart: #3821 [Fix missing qualifiers in reactive messaging](https://github.com/quarkusio/quarkus/pull/3821), by [cescoffier](https://github.com/cescoffier)

:purple_heart: #3819 [Remove Elytron SSL dependencies](https://github.com/quarkusio/quarkus/pull/3819), by [stuartwdouglas](https://github.com/stuartwdouglas)

:purple_heart: #3816 [Test Keycloak in CI](https://github.com/quarkusio/quarkus/pull/3816), by [stuartwdouglas](https://github.com/stuartwdouglas)

:purple_heart: #3815 [Drop useless Class.forName from generated Spring Data JPA repositories](https://github.com/quarkusio/quarkus/pull/3815), by [geoand](https://github.com/geoand)

:purple_heart: #3814 [Ensure the Kubernetes extension doesn't register too much reflection for Jackson](https://github.com/quarkusio/quarkus/pull/3814), by [geoand](https://github.com/geoand)

:purple_heart: #3812 [Upgrade narayana.version to 5.9.8.Final](https://github.com/quarkusio/quarkus/pull/3812), by [gwenneg](https://github.com/gwenneg)

:purple_heart: #3810 [Drop jboss-invocation and start working on JDK 12+ proxy creation](https://github.com/quarkusio/quarkus/pull/3810), by [geoand](https://github.com/geoand)

:purple_heart: #3809 [Tweak the configuration reference generation](https://github.com/quarkusio/quarkus/pull/3809), by [FroMage](https://github.com/FroMage)

:purple_heart: #3807 [Add gradle.properties to the gradle plugin project](https://github.com/quarkusio/quarkus/pull/3807), by [aloubyansky](https://github.com/aloubyansky)

:purple_heart: #3805 [Upgrade to RESTEasy 4.3.0.Final](https://github.com/quarkusio/quarkus/pull/3805), by [asoldano](https://github.com/asoldano)

:purple_heart: #3801 [fix quarkus-smallrye-reactive-messaging-amqp artifactId in bom](https://github.com/quarkusio/quarkus/pull/3801), by [cescoffier](https://github.com/cescoffier)

:purple_heart: #3800 [Rename Subclass method](https://github.com/quarkusio/quarkus/pull/3800), by [stuartwdouglas](https://github.com/stuartwdouglas)

:purple_heart: #3799 [Add the ability to detect if a blocking op is performed in the IO thread](https://github.com/quarkusio/quarkus/pull/3799), by [stuartwdouglas](https://github.com/stuartwdouglas)

:purple_heart: #3798 [Fix CI](https://github.com/quarkusio/quarkus/pull/3798), by [stuartwdouglas](https://github.com/stuartwdouglas)

:purple_heart: #3794 [Fix maven cache on windows](https://github.com/quarkusio/quarkus/pull/3794), by [stuartwdouglas](https://github.com/stuartwdouglas)

:purple_heart: #3793 [#3787 handle different sources of migrations files](https://github.com/quarkusio/quarkus/pull/3793), by [dcdh](https://github.com/dcdh)

:purple_heart: #3789 [TestScopeManager. tearDown() calls setup() instead of tearDown() Fixes issue #3784](https://github.com/quarkusio/quarkus/pull/3789), by [vsevel](https://github.com/vsevel)

:purple_heart: #3788 [Add MicroProfile OpenAPI TCK](https://github.com/quarkusio/quarkus/pull/3788), by [kenfinnigan](https://github.com/kenfinnigan)

:purple_heart: #3780 [Fix example snippet typo containing double ']'](https://github.com/quarkusio/quarkus/pull/3780), by [tarilabs](https://github.com/tarilabs)

:purple_heart: #3776 [Vert.x Event Bus Codec Management](https://github.com/quarkusio/quarkus/pull/3776), by [cescoffier](https://github.com/cescoffier)

:purple_heart: #3772 [Take into account application context path and metrics path](https://github.com/quarkusio/quarkus/pull/3772), by [jmartisk](https://github.com/jmartisk)

:purple_heart: #3771 [Implement mechanism to ignore ReflectiveHierarchyStep warnings ...](https://github.com/quarkusio/quarkus/pull/3771), by [tarilabs](https://github.com/tarilabs)

:purple_heart: #3746 [ Update to vertx 3.8.1](https://github.com/quarkusio/quarkus/pull/3746), by [cescoffier](https://github.com/cescoffier)

:purple_heart: #3736 [Move Jaeger metrics in vendor instead of base](https://github.com/quarkusio/quarkus/pull/3736), by [loicmathieu](https://github.com/loicmathieu)

:purple_heart: #3735 [Correctly add class path entries](https://github.com/quarkusio/quarkus/pull/3735), by [dmlloyd](https://github.com/dmlloyd)

:purple_heart: #3733 [Reactive MySQL client extension](https://github.com/quarkusio/quarkus/pull/3733), by [tsegismont](https://github.com/tsegismont)

:purple_heart: #3688 [Add support for Jackson's JsonPOJOBuilder](https://github.com/quarkusio/quarkus/pull/3688), by [misl](https://github.com/misl)

:purple_heart: #3428 [Generate Asciidoc configuration file for each extension](https://github.com/quarkusio/quarkus/pull/3428), by [machi1990](https://github.com/machi1990)



 - - - 

# COMMITS

Last week there were 138 commits.

:hammer_and_wrench: [Merge pull request #3885 from cescoffier/features/set-timeout-for-native-build  [POC] set timeout for each native build to detect unexpected duration increase](https://github.com/quarkusio/quarkus/commit/fc19abe4f2cd8161f0fb2c8b182e1d4898246fca) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3872 from machi1990/3857  fix(swagger-ui): throw an error when "/" is set as swagger-ui path](https://github.com/quarkusio/quarkus/commit/8300ebe3b4c3c0f4c941adf4ceb81e4c9ca1d61c) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3882 from cescoffier/features/fix-IOThreadDetector-to-use-Vertx-Context  Fix the isInIOThread detection](https://github.com/quarkusio/quarkus/commit/bc1b30d6be905824901179c138ba8f74139ff757) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3891 from lordofthejars/patch-2  Put the same style in the reactive drivers table](https://github.com/quarkusio/quarkus/commit/0be2b876474002210816ab8c889b142d5e56b914) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Put same style in reactive drivers table  Put same style in reactive drivers table](https://github.com/quarkusio/quarkus/commit/d8fcc18c2e95b5f768b7c5d0d3d5b807569ab325) by [lordofthejars](https://github.com/lordofthejars)

:hammer_and_wrench: [Merge pull request #3793 from dcdh/#3787  #3787 handle different sources of migrations files](https://github.com/quarkusio/quarkus/commit/035487279c0697c950fef907bfb8cec02c282d7d) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [fix(swagger-ui): throw an error when "/" is set as swagger-ui path  The value blocks the application from serving anything else - see https://github.com/quarkusio/quarkus/issues/3857#issuecomment-528149421](https://github.com/quarkusio/quarkus/commit/085b2bbc19443ba09294b35415d5055c643b95d7) by [machi1990](https://github.com/machi1990)

:hammer_and_wrench: [Merge pull request #3880 from geoand/spring-value-constructor  Add support for Spring's @Value in a constructor](https://github.com/quarkusio/quarkus/commit/71e856d7ea9c526776bc0b84a1a6f52c0eb28fb8) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Merge pull request #3877 from gsmet/more-config-doc-improvements  More config doc improvements](https://github.com/quarkusio/quarkus/commit/4d3f9f074aaf89584bc5f134df7f4d83f6c518db) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Merge pull request #3865 from jmartisk/master-issue-3838  Don't append @Dependent to REST endpoints](https://github.com/quarkusio/quarkus/commit/2ab50247881153845420268421329043fd1e94fd) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [Merge pull request #3875 from geoand/spring-web-feature  Add missing spring-web feature](https://github.com/quarkusio/quarkus/commit/e22f8576aeecd3f1e832f80ef6567eb688116406) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [set timeout for each native build to detect unexpected duration increase](https://github.com/quarkusio/quarkus/commit/28e9032fec6f2bf5453220c8c93a82ccc4632e56) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Fix the isInIOThread detection to check if we are on an event loop thread.  The current check returns true even if we are on a Vert.x worker thread. Worker thread are not io thread.](https://github.com/quarkusio/quarkus/commit/65ced559f1468d69823d94414f606397930e6939) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Add support for Spring's @Value in a constructor](https://github.com/quarkusio/quarkus/commit/bb3bdab10b325ae7e3315329668f3d84e0a2372c) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [Add type format note to the details too  It was only displayed in the summary table, whereas it makes sense to have it in the details too.](https://github.com/quarkusio/quarkus/commit/57f3f2ace5d2fdad22b34848325fdd8464506675) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Always add a dot at the end of the first line for consistency.  A lot of simple configuration elements don't have a dot at the end so let's be consistent and add one if we couldn't find one.](https://github.com/quarkusio/quarkus/commit/83ff67d42efed44621bef955c32aaef235ce4264) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Add a title to the lifecycle icons](https://github.com/quarkusio/quarkus/commit/14a55efafa421896424ffa197f4d65b828b065e3) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Properly center the elements of the table](https://github.com/quarkusio/quarkus/commit/d0e4dbfb114a9798fbf14aeea24f3db57cad3868) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Add missing spring-web feature](https://github.com/quarkusio/quarkus/commit/715abbd3309d73249bfd2d5630407cee5f87bc90) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [Switch to using Font Awesome icons instead of emojis  This way, the layout will be consistent on all browsers.](https://github.com/quarkusio/quarkus/commit/b58b8839e8d2cd6eb36571506e2f37ceefeac768) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Adjust the generation of the enum values](https://github.com/quarkusio/quarkus/commit/9ac13be65477538fc108cb8aa591b3abda51890f) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Merge pull request #3809 from FroMage/config-tweaks  Tweak the configuration reference generation](https://github.com/quarkusio/quarkus/commit/383767c14ae7705ba21aa81b1256914106e38f6a) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Don't append @Dependent to REST endpoints. Fixes #3838](https://github.com/quarkusio/quarkus/commit/d027cd045cfd9965437d594b8fe5e5af12509b74) by [jmartisk](https://github.com/jmartisk)

:hammer_and_wrench: [Merge pull request #3848 from machi1990/3818  makes inclusion of generated docs optional](https://github.com/quarkusio/quarkus/commit/3d8aa5c165ced6f22505855c11bd01e8fff3bf9d) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Merge pull request #3830 from kenfinnigan/srye-ft-metrics  Update to latest SmallRye Metrics and Fault Tolerance](https://github.com/quarkusio/quarkus/commit/e9da5d3c5534934eac02502dd6205d6eceda38ae) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3858 from machi1990/fix-generated-doc  fix: file not found exception during doc generation](https://github.com/quarkusio/quarkus/commit/90e29af72be52abaf0a3d2fd309e14c0e5ca972e) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [#3787 Use try-with-resources as specified in documentation https://docs.oracle.com/javase/8/docs/api/java/nio/file/Files.html#walk-java.nio.file.Path-java.nio.file.FileVisitOption...-](https://github.com/quarkusio/quarkus/commit/b12212451b6bc69055d721dd0ee7110c77e1fe96) by [dcdh](https://github.com/dcdh)

:hammer_and_wrench: [#3787 handle different sources of migrations files  In case migration files are presents on an external jar, the external jar must be unzipped to avoid FileSystemNotFoundException](https://github.com/quarkusio/quarkus/commit/54b13cc5e5fd8d86d1535a5aa58f4145e56252b1) by [dcdh](https://github.com/dcdh)

:hammer_and_wrench: [Fix failing test](https://github.com/quarkusio/quarkus/commit/f99a117e23134dcdd5dc39dd1340d7ef0f24cf2d) by [kenfinnigan](https://github.com/kenfinnigan)

:hammer_and_wrench: [Update to latest SmallRye Metrics and Fault Tolerance](https://github.com/quarkusio/quarkus/commit/d5854b1b833a3f6a40d32b945dc11588406011ca) by [kenfinnigan](https://github.com/kenfinnigan)

:hammer_and_wrench: [fix: file not found exception during doc generation](https://github.com/quarkusio/quarkus/commit/81b5d99d5e03807ed5f9113a54a721b40f9e0d54) by [machi1990](https://github.com/machi1990)

:hammer_and_wrench: [docs: makes inclusion of generated docs optional  Fixes #3818](https://github.com/quarkusio/quarkus/commit/a31f5f4b271feff9ebb238ab488fc8dc53c05601) by [machi1990](https://github.com/machi1990)

:hammer_and_wrench: [Merge pull request #3849 from stuartwdouglas/3844  Fixes #3844](https://github.com/quarkusio/quarkus/commit/0c95bc6aa98bddac897daaceee1d23e190598d21) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Config docuemntation generator: Backtick enum values](https://github.com/quarkusio/quarkus/commit/1647da639c6fffb503016fa825c330d0bfa13c67) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Merge pull request #3776 from cescoffier/features/fix-generic-codec  Vert.x Event Bus Codec Management](https://github.com/quarkusio/quarkus/commit/266c61cbfaff9dac6622e13cdc3362692f30b8ee) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Merge pull request #3735 from dmlloyd/fix-3592  Correctly add class path entries](https://github.com/quarkusio/quarkus/commit/7a0679e6cd06084a3aa8db2b74bd08fdec1dc3a7) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Merge pull request #3841 from mkouba/issue-3829  Null normal scoped producers throw IllegalProductException](https://github.com/quarkusio/quarkus/commit/10a7e6f7d5b81c6aaeeb03a22d07e8dd26ce61bc) by [mkouba](https://github.com/mkouba)

:hammer_and_wrench: [Merge pull request #3845 from gsmet/fix-error-page  Fix error page layout and appearance](https://github.com/quarkusio/quarkus/commit/f8ade1f3ede328899a16a69d8347e6c5006d6a50) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Merge pull request #3800 from stuartwdouglas/name-conflic  Rename Subclass method](https://github.com/quarkusio/quarkus/commit/c5fae9599991bd827f0b996e6cd6a501a0cca618) by [mkouba](https://github.com/mkouba)

:hammer_and_wrench: [Fixes #3844  Update the next retry time immeditaly](https://github.com/quarkusio/quarkus/commit/87638416ed2fb7c98f250f9313e400687d908c2b) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3839 from marcinczeczko/dynamodb-enable-async  DynamoDB: Re-enable async support](https://github.com/quarkusio/quarkus/commit/ddfce9ef10b99060e571a255931f5f14444eda51) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Null normal scoped producers throw IllegalProductException  - resolves #3829](https://github.com/quarkusio/quarkus/commit/7679ea7836499bad848831526155183eab59e3e2) by [mkouba](https://github.com/mkouba)

:hammer_and_wrench: [Remove Subclass#destroy() and rename generated method to arc$destroy()](https://github.com/quarkusio/quarkus/commit/61633c8e4f1e244bbf9fe4f82cc719fd8cb87ddd) by [mkouba](https://github.com/mkouba)

:hammer_and_wrench: [Merge pull request #3843 from lordofthejars/patch-1  Fixes column number in Infinispan guide from 3 to 4.](https://github.com/quarkusio/quarkus/commit/6223eaf8ec9c222dc0d160749c46b9e17c1b44bb) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Register some default writers for RESTEasy  Fixes #3820](https://github.com/quarkusio/quarkus/commit/7fd45c42dfaab3074cb943a5cdbb08996ce3dcce) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Fix error page layout and improve 404 page layout  They now have a totally consistent look and the stacktrace are properly displayed.  Fixes #3840](https://github.com/quarkusio/quarkus/commit/49a63ce004a31e4f9b5f6c4fcd0b003c147680d7) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Fixes column problem.](https://github.com/quarkusio/quarkus/commit/d0f4329e6fe9b4d7eca5d88e45a20f40203b808a) by [lordofthejars](https://github.com/lordofthejars)

:hammer_and_wrench: [DynamoDB: Upgrade AWS SDK to 2.8.0 to support Netty 4.1.29, enable async support](https://github.com/quarkusio/quarkus/commit/bbc45edf2902da1d2aee021cf0a3f6615a72400a) by [marcinczeczko](https://github.com/marcinczeczko)

:hammer_and_wrench: [Merge pull request #3805 from asoldano/resteasy430  Upgrade to RESTEasy 4.3.0.Final](https://github.com/quarkusio/quarkus/commit/c9cb3ed2eccb6fb70ba59a334be92b6912a72cbc) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3816 from stuartwdouglas/keycloak-test  Test Keycloak in CI](https://github.com/quarkusio/quarkus/commit/915be5672459af3805546f2eea1d37e357c5e7a3) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [Merge pull request #3837 from stuartwdouglas/test-fix  Fix intermittent failures in ImportSqlHotReloadScriptTestCase](https://github.com/quarkusio/quarkus/commit/e39a8ca9152353672c956e6cf587ce8144d891a4) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [Merge pull request #3819 from stuartwdouglas/elytron-ssl  Remove Elytron SSL dependencies](https://github.com/quarkusio/quarkus/commit/cda4bea2d69231c308f20dd26debfc96777ae948) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Test Keycloak in CI](https://github.com/quarkusio/quarkus/commit/680fa91a875b293269a1a6fe386853b1a3bab60c) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Fix intermittent failures in ImportSqlHotReloadScriptTestCase](https://github.com/quarkusio/quarkus/commit/382d6b5c766ba25dc5143860c68c0422061a4f88) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Remove Elytron SSL dependencies  These are not needed in core after the HTTP changes](https://github.com/quarkusio/quarkus/commit/f56a0694d4d90f5960cf3bd6e08181995f2a91ad) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3826 from kenfinnigan/srye-health  Update to latest SmallRye Health](https://github.com/quarkusio/quarkus/commit/01e6d14d1f3f6c76b6afd69c31a04508e43fb18e) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Register FilterConfigSourceImpl and ServletContextConfigSourceImpl](https://github.com/quarkusio/quarkus/commit/044b60c43b3d00003e97ceab17bb440c13c3b400) by [asoldano](https://github.com/asoldano)

:hammer_and_wrench: [Merge pull request #3824 from loicmathieu/feat/upgrade-flyway-6  Upgrade Flyway 6.0.1](https://github.com/quarkusio/quarkus/commit/0795073f1264752101a49fec3338bdef9005182d) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3825 from kenfinnigan/srye-jwt  Update to latest SmallRye JWT](https://github.com/quarkusio/quarkus/commit/cce9f9cf9f0f9ec9da8ee11af3064b6963ace0fc) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3827 from kenfinnigan/srye-tracing  Update to latest SmallRye OpenTracing](https://github.com/quarkusio/quarkus/commit/db2e7d67d976c21f9a6906a15668602cb5c60555) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3814 from geoand/jackson-k8s-client  Ensure the Kubernetes extension doesn't register too much reflection for Jackson](https://github.com/quarkusio/quarkus/commit/899e1cde7616e4ab640ac4fbc1d7330dcd435a80) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3821 from cescoffier/features/fix-reactive-messaging-qualifiers  Fix missing qualifiers in reactive messaging](https://github.com/quarkusio/quarkus/commit/3eacfc753d5cf42e3745382792aa3b9b30ee2790) by [kenfinnigan](https://github.com/kenfinnigan)

:hammer_and_wrench: [Merge pull request #3835 from gunnarmorling/patch-8  Fixing broken list rendering](https://github.com/quarkusio/quarkus/commit/d9967f3494cca82f1455e032dc9fe759febed9eb) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Fixing broken list rendering](https://github.com/quarkusio/quarkus/commit/12c156e03676843242da23fcaac7298543d1808b) by [gunnarmorling](https://github.com/gunnarmorling)

:hammer_and_wrench: [Merge pull request #3807 from aloubyansky/3804  Add gradle.properties to the gradle plugin project](https://github.com/quarkusio/quarkus/commit/f96767d383652f73c1506a19ad3b568f54c1e4e5) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Update to latest SmallRye OpenTracing](https://github.com/quarkusio/quarkus/commit/672b029de3e46d4b65f2417e20bfd927e65e7d78) by [kenfinnigan](https://github.com/kenfinnigan)

:hammer_and_wrench: [Update to latest SmallRye Health](https://github.com/quarkusio/quarkus/commit/557422140696e31c25c99e18d9ec926f48ec19cc) by [kenfinnigan](https://github.com/kenfinnigan)

:hammer_and_wrench: [Update to latest SmallRye JWT](https://github.com/quarkusio/quarkus/commit/2e321ef946177afac82c33d991a174a3b807c1e9) by [kenfinnigan](https://github.com/kenfinnigan)

:hammer_and_wrench: [Correctly add class path entries  Fixes #3592](https://github.com/quarkusio/quarkus/commit/997827cf7077e152b3b31d06010127415dd023d7) by [dmlloyd](https://github.com/dmlloyd)

:hammer_and_wrench: [Merge pull request #3815 from geoand/spring-data-class-forname  Drop useless Class.forName from generated Spring Data JPA repositories](https://github.com/quarkusio/quarkus/commit/39caf199aa199037046d29eb4a98b26d3eac6488) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [Fix missing qualifiers in reactive messaging](https://github.com/quarkusio/quarkus/commit/fc8b819a09421f7d57b9ed33ab34b26d368e54ee) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Register new ServletConfigSourceImpl type for reflection](https://github.com/quarkusio/quarkus/commit/33184fc9829bb802ca81f3da575cd0d4ed0046a8) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Drop useless Class.forName from generated Spring Data JPA repositories](https://github.com/quarkusio/quarkus/commit/c6ca6e18ec78624d93058fe49472c92a5d33f940) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [Merge pull request #3799 from stuartwdouglas/blocking-op-detection  Add the ability to detect if a blocking op is performed in the IO thread](https://github.com/quarkusio/quarkus/commit/7404e8e0f2f3ed83f3259eac39770aff2c75a9f3) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Merge pull request #3810 from geoand/drop-classwriter  Drop jboss-invocation and start working on JDK 12+ proxy creation](https://github.com/quarkusio/quarkus/commit/b66686494651d54e7d06bb34417c77793d30f3b8) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Include simple type in bottom descrption](https://github.com/quarkusio/quarkus/commit/2a6d792cf702ebe96e3741e029d523a43ce073fb) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Don't javadoc for String, Path](https://github.com/quarkusio/quarkus/commit/1c73cea908f2aa511efe9fe48f01e847637252dd) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Fixed doc generator test with my changes](https://github.com/quarkusio/quarkus/commit/c460fddc485beebcf67396a921d268592e89e580) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Merge pull request #3801 from cescoffier/features/fix-typo-in-artifactid  fix quarkus-smallrye-reactive-messaging-amq artifactId in bom](https://github.com/quarkusio/quarkus/commit/dc2206472ffd93d2aa95ba9e88c8d31f9ace7bae) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Ensure Kubernetes ext doesn't register too much reflection for Jackson](https://github.com/quarkusio/quarkus/commit/d434559f631760071a802158b032fca67a2c153c) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [Merge pull request #3788 from kenfinnigan/openapi-tck  Add MicroProfile OpenAPI TCK](https://github.com/quarkusio/quarkus/commit/7e39b8b09ca5a49f5309b08f0a762f2c975aae2b) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Rework the Event bus codec integration  * Make the local codec implementation available for user if they want to extend it * Improve codec detection and registration * Enforce local delivery * Add tests and integration tests](https://github.com/quarkusio/quarkus/commit/de8fab818a4c6d91fa686e0b651635c21cf0c75b) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Merge pull request #3812 from gwenneg/issue-3678-narayana-jandex-warning  Upgrade narayana.version to 5.9.8.Final](https://github.com/quarkusio/quarkus/commit/07ffedf6085ed1a46af78aad4f4f1474c0757261) by [gsmet](https://github.com/gsmet)

:hammer_and_wrench: [Upgrade narayana.version to 5.9.8.Final](https://github.com/quarkusio/quarkus/commit/b56704432036fcb6c61ddf4dce2daa0aab33ed8e) by [gwenneg](https://github.com/gwenneg)

:hammer_and_wrench: [WIP - Allow the creation of proxies in JDK 12+](https://github.com/quarkusio/quarkus/commit/2e41ebef2d39863ceb3a888f408950509697c3c6) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [config doc: turn Class<?> into "class name"](https://github.com/quarkusio/quarkus/commit/93d68cf56bff70115a0ee451bf3f6461e2115b67) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Config doc: list enum values](https://github.com/quarkusio/quarkus/commit/cfff710b14d019dbd977663fa08756bc776e3a48) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Config doc: tweak column sizes, add first sentence](https://github.com/quarkusio/quarkus/commit/5480ad23a21dc4c2d3143360844fe87ab6428e8f) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Config docs: turn primitive wrappers into primitives as far as docs are concerned](https://github.com/quarkusio/quarkus/commit/88e360902815138f505f8d69af649d8b438f82da) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Replace jboss-invocation with Gizmo based ProxyFactory  This is first step to allow the project to build on JDK 12+ Relates to: #1534](https://github.com/quarkusio/quarkus/commit/51910fe5d2d20213d383e0fab31809ae48112b56) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [Merge pull request #3733 from tsegismont/mysql-client  Reactive MySQL client extension](https://github.com/quarkusio/quarkus/commit/076d00ca09671e659c3a6548bd48543c10f95a1b) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Add gradle.properties to the gradle plugin project](https://github.com/quarkusio/quarkus/commit/6a417e68a455d65fc89c503abae1ce4a8c7a5d27) by unknown author

:hammer_and_wrench: [Upgrade to RESTEasy 4.3.0.Final](https://github.com/quarkusio/quarkus/commit/a69ae3ba18b84cf371a5ced91f0614f5f16d1dd8) by [asoldano](https://github.com/asoldano)

:hammer_and_wrench: [Renamed "Reactive Database Clients" to "Reactive SQL Clients"](https://github.com/quarkusio/quarkus/commit/7e23f34920461f168ef545d12f961fa187e51fc7) by [tsegismont](https://github.com/tsegismont)

:hammer_and_wrench: [Documentation update](https://github.com/quarkusio/quarkus/commit/eef4e431927ef1a4b47d31fe6f15a9435b8b022f) by [tsegismont](https://github.com/tsegismont)

:hammer_and_wrench: [Reactive MySQL client extension  New extension similar to the Postgres extension (no shared code yet). Integrations tests with MariaDB.](https://github.com/quarkusio/quarkus/commit/a42def67eeb00f4eb6958c5f4ba6c4a9e792075c) by [tsegismont](https://github.com/tsegismont)

:hammer_and_wrench: [Merge pull request #3428 from machi1990/generate-config-properties-doc  Generate Asciidoc configuration file for each extension](https://github.com/quarkusio/quarkus/commit/c519e38da9fc4c588c9bdde02c2d4c5861a239e5) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Register GenericCodec for reflection  Fix https://github.com/quarkusio/quarkus-quickstarts/issues/265](https://github.com/quarkusio/quarkus/commit/a9574c2074948fbda7daf51056390f2b9eea12d8) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [fix artifactId in bom - the  segment was missing](https://github.com/quarkusio/quarkus/commit/75a314d2e80efc735d7e28147dbf750ed4af80f0) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Rename Subclass method  The current name has a high chance of conflicting, e.g. HttpFilter.destroy()](https://github.com/quarkusio/quarkus/commit/72d49aca52d4394e6b16b976576fd7e0ac0fa95d) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Add the ability to detect if a blocking op is performed in the IO thread](https://github.com/quarkusio/quarkus/commit/a669395416370755452ab664f8c721fc3254d073) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3798 from stuartwdouglas/cifix  Fix CI](https://github.com/quarkusio/quarkus/commit/c36d05b15b942254159e8d3f8bccdd7986407daa) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Fix CI](https://github.com/quarkusio/quarkus/commit/df85a95d8bd252cbf78295ac7e5562a4017e50d9) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3746 from cescoffier/features/update-to-vertx-3.8.1   Update to vertx 3.8.1](https://github.com/quarkusio/quarkus/commit/b433e9e1a23bcc90a8ba596f22a66d4836948c2d) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3794 from stuartwdouglas/windows-cache  Fix maven cache on windows](https://github.com/quarkusio/quarkus/commit/85ace8a46a175a48b07eed72144fdb6dfc83c002) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [Merge pull request #3789 from vsevel/issue_3784  TestScopeManager. tearDown() calls setup() instead of tearDown() Fixes issue #3784](https://github.com/quarkusio/quarkus/commit/1a03393f5c7d1f1a1b378d9048132b116745c083) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [TestScopeManager. tearDown() calls setup() instead of tearDown() #3784](https://github.com/quarkusio/quarkus/commit/7b04b1dfefbccb191133e968f8b57a4ea9436f68) by [vsevel](https://github.com/vsevel)

:hammer_and_wrench: [Fix maven cache on windows](https://github.com/quarkusio/quarkus/commit/8ce3d73dab246e1afe027403bf91e31d0729225b) by [stuartwdouglas](https://github.com/stuartwdouglas)

:hammer_and_wrench: [Merge pull request #3688 from misl/Fix_3652  Add support for Jackson's JsonPOJOBuilder](https://github.com/quarkusio/quarkus/commit/79edb31a47cc4102b608f339c4cc20525c240cd0) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [Added support for @JsonPOJOBuilder annotated classes as reflectiveClass - Use @JsonDeserialize (instead of @JsonPOJOBuilder) to add reflective classes. - Both model and builder are added - Added safeguard for @JsonDeserialize without builder - Transformed reproducer project into integration tests for jackson extension. - Added support for models and model builders with inheritance](https://github.com/quarkusio/quarkus/commit/7358057e3fe87356ac250e2de0ce8c4f31612f44) by [misl](https://github.com/misl)

:hammer_and_wrench: [TestScopeManager. tearDown() calls setup() instead of tearDown() #3784](https://github.com/quarkusio/quarkus/commit/e1cbf365e161899144498cf829cd8ecf087643de) by [vsevel](https://github.com/vsevel)

:hammer_and_wrench: [Temporary disable the async client of dynamoDB until the AWS SDK becomes compatible with the netty version we ship. More details on https://github.com/aws/aws-sdk-java-v2/issues/1399, https://github.com/aws/aws-sdk-java-v2/issues/1344 and https://github.com/aws/aws-sdk-java-v2/pull/1391](https://github.com/quarkusio/quarkus/commit/22750e66e17e91cbe3c4157508a08dc149c06736) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Add MicroProfile OpenAPI TCK](https://github.com/quarkusio/quarkus/commit/84a6531957db13f8bd9d181f5c1d20f77f8cd1fd) by [kenfinnigan](https://github.com/kenfinnigan)

:hammer_and_wrench: [docs: generate a table summary of config items  generate a table summary with a key column pointing on the description part and a type column with a link pointing to the javadoc site of configuration types used by the extension: currently only official java doc site, vertx javadoc and agroal doc site are supported.](https://github.com/quarkusio/quarkus/commit/1678108e7523f32ff9df2b61b4213d20f1e50ddb) by [machi1990](https://github.com/machi1990)

:hammer_and_wrench: [docs: orders map config key to the end of the generated doc before writing it.  also reviews displaying of config phase legend](https://github.com/quarkusio/quarkus/commit/eb8c71366ca35a7aaca9e2f9ac883d475ac06ded) by [machi1990](https://github.com/machi1990)

:hammer_and_wrench: [docs: generate config item using the same source code declaration order . Correctly format generated docs for better rendering by AsciiDoc](https://github.com/quarkusio/quarkus/commit/475068c624d9adc918e43fb878c21b6fd12b98f1) by [machi1990](https://github.com/machi1990)

:hammer_and_wrench: [docs: properly parse docs](https://github.com/quarkusio/quarkus/commit/c3621f2f1ddf7603a5396d00adff3991d7f3be25) by [machi1990](https://github.com/machi1990)

:hammer_and_wrench: [docs: display correct default value for primitives instead of an empty string  .Also ignore CongitRoot and ConfigGroup static fields](https://github.com/quarkusio/quarkus/commit/fe53a63232b3c693b0da953c207048fdae14c73f) by [machi1990](https://github.com/machi1990)

:hammer_and_wrench: [docs: generate output file per extension](https://github.com/quarkusio/quarkus/commit/c057dbf947cba8f592796a2459d5b43330e04c53) by [machi1990](https://github.com/machi1990)

:hammer_and_wrench: [docs: generate config docs  output generated docs in docs/src/main/asciidoc/generated](https://github.com/quarkusio/quarkus/commit/2607d60638f3b51b7b5d00863057f6d34027c050) by [machi1990](https://github.com/machi1990)

:hammer_and_wrench: [Delay the initialisation of the VertxHttp2ClientUpgradeCodec to avoid a GraallVM compilation issue.  This issue was rasied when the application uses a WebClient.](https://github.com/quarkusio/quarkus/commit/66329c5f9a74f272557715f6ade7ccf56b621269) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Fix Netty substitutions related to SSL](https://github.com/quarkusio/quarkus/commit/c7127e13f23cfa77fb1c3652ad13802d25b7724a) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Remove substitution contained in the upstream netty artifact](https://github.com/quarkusio/quarkus/commit/60f499f49ba609d846c5b50de90ae05f64e0e1b7) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Bump netty version to 4.1.39.Final](https://github.com/quarkusio/quarkus/commit/797d0f529038d67031a74d5966f08fce351e6b69) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Add support for emitter injection in methods and constructors](https://github.com/quarkusio/quarkus/commit/646e4591e7ae02417d6c6c257e8c7bf9fc54b9fa) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Handle other kind of injection point (method, parameter...) Handle hwne bufferSize is not set](https://github.com/quarkusio/quarkus/commit/dfecfb48f953e3d7ff4900974d7ea4fa51ae89ad) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Update Quarkus-HTTP version to use Vert.x 3.8.1](https://github.com/quarkusio/quarkus/commit/679ef2b9f46fa8c38eb55fbd24fc04199fc80ff4) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Make the EmiterBuildItem immutable](https://github.com/quarkusio/quarkus/commit/913f0ec1eb42ada26f5b1a54d41eedc105c6ce44) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Add missing Reactive Streams Ops dependency to the quarkus-vertx runtime](https://github.com/quarkusio/quarkus/commit/41e69420dff30383fbbaa5ddfe28ce1c9089ef51) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Extend emitter support to support back-pressure control](https://github.com/quarkusio/quarkus/commit/6651067fc67fcab6112475b282d56b0da9633c6a) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Update vert.x version to 3.8.1 as well as companions (Axle to 0.0.9, SR Reactive messaging to 1.0.3, SR reactive streams operators to 1.0.9) Rename the artifactId of the SmallRye artifacts that went through the name refactoring.](https://github.com/quarkusio/quarkus/commit/2fef324c179ee03c983b254483bb607ee9e77f8a) by [cescoffier](https://github.com/cescoffier)

:hammer_and_wrench: [Merge pull request #3736 from loicmathieu/fix/jaeger-metrics-in-base  Move Jaeger metrics in vendor instead of base](https://github.com/quarkusio/quarkus/commit/3993977603cce25d94a9f111ae4ea36f673b3fbc) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Merge pull request #3772 from jmartisk/master-issue-3745  Take into account application context path and metrics path](https://github.com/quarkusio/quarkus/commit/5fd1a57eb423fd95e3045feecf39ccb7a284dccd) by [FroMage](https://github.com/FroMage)

:hammer_and_wrench: [Merge pull request #3771 from tarilabs/tarilabs-20190829  Implement mechanism to ignore ReflectiveHierarchyStep warnings ...](https://github.com/quarkusio/quarkus/commit/59ca4bad56699da22ec74dffe825d094d44c26df) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [feat: upgrade to flyway 6](https://github.com/quarkusio/quarkus/commit/38280358d8cf04b91dad7ef5a9d463823f8ae675) by [loicmathieu](https://github.com/loicmathieu)

:hammer_and_wrench: [Merge pull request #3780 from tarilabs/patch-1  Fix example snippet typo containing double ']'](https://github.com/quarkusio/quarkus/commit/a7c913fdb3f8852e3b7455ab37b1d6ad6f78064e) by [geoand](https://github.com/geoand)

:hammer_and_wrench: [Implement mechanism to ignore ReflectiveHierarchyStep warnings ...  ... and leverage this as needed in Kogito extension implement code review feedback from 	@geoand implement code review feedback from @mswiderski](https://github.com/quarkusio/quarkus/commit/bb02afb51e44663e3ff5ffb386042e6a506304e4) by [tarilabs](https://github.com/tarilabs)

:hammer_and_wrench: [Fix example snippet typo containing double ']'  Taking reference default for example https://github.com/quarkusio/quarkus/blob/master/docs/src/main/asciidoc/logging-guide.adoc#run-time-configuration  Change typo in the example logging configuration snippet  ``` from: [%c{2.}]]   to: [%c{2.}] ```](https://github.com/quarkusio/quarkus/commit/40aa0bf3418357b648bec5ddbdd05fff1c8798f8) by [tarilabs](https://github.com/tarilabs)



 - - - 

# CONTRIBUTORS

Last week there were 21 contributors.

:bust_in_silhouette: [stuartwdouglas](https://github.com/stuartwdouglas)

:bust_in_silhouette: [gsmet](https://github.com/gsmet)

:bust_in_silhouette: [lordofthejars](https://github.com/lordofthejars)

:bust_in_silhouette: [machi1990](https://github.com/machi1990)

:bust_in_silhouette: [geoand](https://github.com/geoand)

:bust_in_silhouette: [cescoffier](https://github.com/cescoffier)

:bust_in_silhouette: [jmartisk](https://github.com/jmartisk)

:bust_in_silhouette: [dcdh](https://github.com/dcdh)

:bust_in_silhouette: [kenfinnigan](https://github.com/kenfinnigan)

:bust_in_silhouette: [FroMage](https://github.com/FroMage)

:bust_in_silhouette: [mkouba](https://github.com/mkouba)

:bust_in_silhouette: [marcinczeczko](https://github.com/marcinczeczko)

:bust_in_silhouette: [asoldano](https://github.com/asoldano)

:bust_in_silhouette: [gunnarmorling](https://github.com/gunnarmorling)

:bust_in_silhouette: [dmlloyd](https://github.com/dmlloyd)

:bust_in_silhouette: [gwenneg](https://github.com/gwenneg)

:bust_in_silhouette: [tsegismont](https://github.com/tsegismont)

:bust_in_silhouette: [vsevel](https://github.com/vsevel)

:bust_in_silhouette: [misl](https://github.com/misl)

:bust_in_silhouette: [loicmathieu](https://github.com/loicmathieu)

:bust_in_silhouette: [tarilabs](https://github.com/tarilabs)



 - - - 

# STARGAZERS

Last week there were no stargazers.



 - - - 

# RELEASES

Last week there was 1 release.

:rocket: [0.21.2 0.21.2](https://github.com/quarkusio/quarkus/releases/tag/0.21.2)



 - - - 



