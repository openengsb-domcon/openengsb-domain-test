openengsb-domain-test-2.0.1 2012-01-09
---------------------------------------------------------------------

Fix release of wsdl-files to maven repository

** Bug
    * [OPENENGSB-2636] - release is missing WSDL-artifact

** Task
    * [OPENENGSB-2637] - Release domain-test-2.0.1

** Known Issues
    * [OPENENGSB-2621] - Domain definition is not suited for distributed builds


openengsb-domain-test-2.0.0 2012-01-09
---------------------------------------------------------------------

This release upgrades the domain to a) work with the OpenEngSB 2.4.0 and b) incorporated the
latest features of the new version (EDB integration, WSDLs for easy bridge integration, dedicated documentation).

** Bug
    * [OPENENGSB-2321] - adapt test domain to current openengsb-framework
    * [OPENENGSB-2582] - Domains and Connectors need to include our snapshot repo to work with deployed snapshots correctly

** Improvement
    * [OPENENGSB-1806] - Enhance test domain with EDB CUD Events
    * [OPENENGSB-2586] - Include issuetracker, buildserver and inceptionYear from root

** New Feature
    * [OPENENGSB-2513] - move documentation to domain
    * [OPENENGSB-2575] - Include wsdl definition from 2.4.0 parent

** Task
    * [OPENENGSB-2254] - Move documentation to domains they belong to.
    * [OPENENGSB-2566] - upgrade openengsb-domain-parent to 2.3.0 in all domains
    * [OPENENGSB-2596] - Adapt domain.name in domains to be e.g. AppointmentDomain instead of Appointment alone
    * [OPENENGSB-2627] - Release domain-test-2.0.0

** Known Issues
    * [OPENENGSB-2621] - Domain definition is not suited for distributed builds


openengsb-domain-test-1.2.1 2011-05-23
---------------------------------------------------------------------

First support release of the Test Domain upgrading to the latest OpenEngSB Framework version and including bundle.info.

** Library Upgrade
    * [OPENENGSB-1508] - Push connectors and domains to latest openengsb-framework-1.3.0.M1
    * [OPENENGSB-1609] - Upgrade openengsb-framework to 1.3.0.M2

** New Feature
    * [OPENENGSB-948] - Add OSGI-INF/bundle.info as used in Karaf to the openengsb bundles

** Task
    * [OPENENGSB-1438] - Release openengsb-domain-test-1.2.1


openengsb-domain-test-1.2.0 2011-04-27
---------------------------------------------------------------------

Initial release of the OpenEngSB Test Domain as standalone package

** Bug
    * [OPENENGSB-1395] - mvn scm tags point to openengsb instead of domain

** Library Upgrade
    * [OPENENGSB-1394] - Upgrade to openengsb-1.2.0.RC1

** Task
    * [OPENENGSB-1322] - adapt domains to new service-manager-api
    * [OPENENGSB-1373] - Release openengsb-domain-test-1.2.0
    * [OPENENGSB-1396] - Add infrastructure for notice file generation
    * [OPENENGSB-1397] - Add ASF2 license file

