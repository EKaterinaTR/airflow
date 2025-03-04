
 .. Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

 ..   http://www.apache.org/licenses/LICENSE-2.0

 .. Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.


Package apache-airflow-providers-google
------------------------------------------------------

Google services including:

  - `Google Ads <https://ads.google.com/>`__
  - `Google Cloud (GCP) <https://cloud.google.com/>`__
  - `Google Firebase <https://firebase.google.com/>`__
  - `Google LevelDB <https://github.com/google/leveldb/>`__
  - `Google Marketing Platform <https://marketingplatform.google.com/>`__
  - `Google Workspace <https://workspace.google.com/>`__ (formerly Google Suite)


This is detailed commit list of changes for versions provider package: ``google``.
For high-level changelog, see :doc:`package information including changelog <index>`.



10.6.0
......

Latest change: 2023-08-04

=================================================================================================  ===========  ===================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ===================================================================================================
`e10aa6ae6a <https://github.com/apache/airflow/commit/e10aa6ae6ad07830cbf5ec59d977654c52012c22>`_  2023-08-04   ``openlineage, bigquery: add openlineage method support for BigQueryExecuteQueryOperator (#31293)``
`e3d82c6be0 <https://github.com/apache/airflow/commit/e3d82c6be0e0e1468ade053c37690aa1e0e4882d>`_  2023-08-04   ``Get rid of Python2 numeric relics (#33050)``
`1ea7ae809b <https://github.com/apache/airflow/commit/1ea7ae809bf0b8d1c8edf97e4d456b3753a1feca>`_  2023-08-03   ``Refactor of links in Dataproc. (#31895)``
`d9121a7b9e <https://github.com/apache/airflow/commit/d9121a7b9e3d2456c1c3cd9c09d8404501a360c8>`_  2023-08-02   ``Fix 'DataFusionAsyncHook' catch 404 (#32855)``
`0c894dbb24 <https://github.com/apache/airflow/commit/0c894dbb24ad9ad90dcb10c81269ccc056789dc3>`_  2023-08-02   ``Handle multiple connections using exceptions (#32365)``
`915f9e4060 <https://github.com/apache/airflow/commit/915f9e40601fbfa3ebcf2fe82ced14191b12ab18>`_  2023-07-31   ``Add GCS Requester Pays bucket support to GCSToS3Operator (#32760)``
`f9cddf332d <https://github.com/apache/airflow/commit/f9cddf332db712ce2121d355dd94c78b392a7bb9>`_  2023-07-31   ``openlineage,gcs: use proper name for openlineage methods (#32956)``
`ce5eebd004 <https://github.com/apache/airflow/commit/ce5eebd00403beabc23b4f0b4bedba5b5c397c42>`_  2023-07-31   ``Fix system test for MetastoreHivePartitionSensor (#32861)``
`c422920c6e <https://github.com/apache/airflow/commit/c422920c6ef9ac2cceb0369cd0ec0989887688d9>`_  2023-07-31   ``Add system test and docs for CloudDataTransferServiceGCSToGCSOperator (#32960)``
=================================================================================================  ===========  ===================================================================================================

10.5.0
......

Latest change: 2023-07-29

=================================================================================================  ===========  =======================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =======================================================================================================
`d06b7af69a <https://github.com/apache/airflow/commit/d06b7af69a65c50321ba2a9904551f3b8affc7f1>`_  2023-07-29   ``Prepare docs for July 2023 3rd wave of Providers (#32875)``
`81b85ebcbd <https://github.com/apache/airflow/commit/81b85ebcbd241e1909793d7480aabc81777b225c>`_  2023-07-29   ``Fix 'BigQueryInsertJobOperator' not exiting deferred state (#31591)``
`9d68492f87 <https://github.com/apache/airflow/commit/9d68492f875464f505afef2ecd81a28d8e4922b8>`_  2023-07-27   ``misc: update MLEngine system tests (#32881)``
`b73366799d <https://github.com/apache/airflow/commit/b73366799d98195a5ccc49a2008932186c4763b5>`_  2023-07-27   ``openlineage, gcs: add openlineage methods for GcsToGcsOperator (#31350)``
`583f407c54 <https://github.com/apache/airflow/commit/583f407c54a6683247a6b8a3aed75a184f8a92c6>`_  2023-07-26   ``Fixup docstring for deprecated DataprocSubmitSparkJobOperator and refactoring system tests (#32743)``
`4c2ef99772 <https://github.com/apache/airflow/commit/4c2ef99772203936cdb6387f099a64ec9aa736f2>`_  2023-07-26   ``Add Spot Instances support with Dataproc Operators (#31644)``
`82e6226738 <https://github.com/apache/airflow/commit/82e6226738bcf7f3981c5b8db714a849c26a6962>`_  2023-07-23   ``Fix Datafusion system tests (#32749)``
`0fbb05a459 <https://github.com/apache/airflow/commit/0fbb05a459f62a14896aa5d863685b449ab3e442>`_  2023-07-21   ``Fixup system test for DataprocSubmitJobOperator (SparkSQL job) (#32745)``
`fbeddc3017 <https://github.com/apache/airflow/commit/fbeddc30178eec7bddbafc1d560ff1eb812ae37a>`_  2023-07-21   ``Fixup docstring for deprecated DataprocSubmitPigJobOperator (#32739)``
`440c9eb2b4 <https://github.com/apache/airflow/commit/440c9eb2b4c834d040584a492e23ff4f1212f7f0>`_  2023-07-21   ``Fixup system test for DataprocSubmitJobOperator (PySpark job) (#32740)``
`49921763eb <https://github.com/apache/airflow/commit/49921763eb15f68f91da826a86690ba4c4155c35>`_  2023-07-21   ``Migrate system test for PostgresToGCSOperator to new design AIP-47 (#32641)``
`978adb309a <https://github.com/apache/airflow/commit/978adb309aee755df02aadab72fdafb61bec5c80>`_  2023-07-21   ``Install sqlalchemy-spanner package into Google provider (#31925)``
`99b8a90346 <https://github.com/apache/airflow/commit/99b8a90346b8826756ac165b73464a701e2c33aa>`_  2023-07-20   ``Filtering and ordering results of DataprocListBatchesOperator (#32500)``
`3c14753b03 <https://github.com/apache/airflow/commit/3c14753b03872b259ce2248eda92f7fb6f4d751b>`_  2023-07-20   ``Fix BigQueryGetDataOperator where project_id is not being respected in deferrable mode (#32488)``
`e8287734cb <https://github.com/apache/airflow/commit/e8287734cbc29d45eeab565936afe8c9eb2e5340>`_  2023-07-20   ``Fixup docstring for deprecated DataprocSubmitHiveJobOperator (#32723)``
`8b7ae76026 <https://github.com/apache/airflow/commit/8b7ae760261109f1bfa6c60abbbc9803bd93bb74>`_  2023-07-20   ``Fixup docs and optimize system test for DataprocSubmitJobOperator (Hadoop job) (#32722)``
`848c69a194 <https://github.com/apache/airflow/commit/848c69a194c03ed3a5badc909e26b5c1bda03050>`_  2023-07-20   ``Refresh GKE OAuth2 tokens (#32673)``
`60c49ab2df <https://github.com/apache/airflow/commit/60c49ab2dfabaf450b80a5c7569743dd383500a6>`_  2023-07-19   ``Add more accurate typing for DbApiHook.run method (#31846)``
`e01323635a <https://github.com/apache/airflow/commit/e01323635a88ecf313a415ea41d32d6d28fa0794>`_  2023-07-13   ``Add deprecation info to the providers modules and classes docstring (#32536)``
=================================================================================================  ===========  =======================================================================================================

10.4.0
......

Latest change: 2023-07-12

=================================================================================================  ===========  ====================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ====================================================================================
`e7f59a913e <https://github.com/apache/airflow/commit/e7f59a913e1fcf9052e69f62af9fe23901f1a358>`_  2023-07-12   ``Prepare docs for July 2023 2nd wave of Providers (#32566)``
`2ad91a7808 <https://github.com/apache/airflow/commit/2ad91a7808e97a70386513e016bdc08dbb8b72d0>`_  2023-07-11   ``Bugfix GCSToGCSOperator when copy files to folder without wildcard (#32486)``
`86c6cc9a9a <https://github.com/apache/airflow/commit/86c6cc9a9aea58dce5c7691717382d6c6911d1e1>`_  2023-07-11   ``Combine 8 into 1 (#29462)``
`3a8da4b55b <https://github.com/apache/airflow/commit/3a8da4b55b363b5b74d78b7d481dc7544afd36cb>`_  2023-07-11   ``Allow a destination folder to be provided (#31885)``
`0f73647bda <https://github.com/apache/airflow/commit/0f73647bdab79ac6c30961222924f6166f75b55a>`_  2023-07-08   ``D205 Support - Provider: Google (#32356)``
`e70bee00cd <https://github.com/apache/airflow/commit/e70bee00cd12ecf1462485a747c0e3296ef7d48c>`_  2023-07-08   ``Fix 'cache_control' parameter of upload function in 'GCSHook'  (#32440)``
`257136786c <https://github.com/apache/airflow/commit/257136786c9a3eebbae717738637ab24fd6ab563>`_  2023-07-08   ``Moves 'AzureBlobStorageToGCSOperator' from Azure to Google provider (#32306)``
`723eb7d453 <https://github.com/apache/airflow/commit/723eb7d453e50fb82652a8cf1f6a538410be777f>`_  2023-07-07   ``Give better link to job configuration docs in BigQueryInsertJobOperator (#31736)``
`6c854dcb16 <https://github.com/apache/airflow/commit/6c854dcb164caffea640b368eda94a2a9166fa97>`_  2023-07-07   ``Migrating Google AutoML example_dags to sys tests (#32368)``
`53d9421905 <https://github.com/apache/airflow/commit/53d9421905c3c268744c3e43601db63bc7b6fa87>`_  2023-07-07   ``build(pre-commit): check deferrable default value (#32370)``
`2d690de110 <https://github.com/apache/airflow/commit/2d690de110825ba09b9445967b47c44edd8f151c>`_  2023-07-07   ``Fix BigQuery transfer operators to respect project_id arguments (#32232)``
`e7587b3369 <https://github.com/apache/airflow/commit/e7587b3369af30848c3cf1c7eff9e801b1440793>`_  2023-07-06   ``Fix the gcp_gcs_delete_objects on empty list (#32383)``
`becfb3c64f <https://github.com/apache/airflow/commit/becfb3c64f42533d6b8c6806c290952d84bc76a0>`_  2023-07-06   ``Fix endless loop of defer in cloud_build (#32387)``
`e4757d6dfa <https://github.com/apache/airflow/commit/e4757d6dfa6e7385eb90c38c60ab8fefa24e7a0e>`_  2023-07-06   ``Fix GCSToGCSOperator copy without wildcard and exact_match=True (#32376)``
=================================================================================================  ===========  ====================================================================================

10.3.0
......

Latest change: 2023-07-06

=================================================================================================  ===========  =============================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =============================================================================================================
`225e3041d2 <https://github.com/apache/airflow/commit/225e3041d269698d0456e09586924c1898d09434>`_  2023-07-06   ``Prepare docs for July 2023 wave of Providers (RC2) (#32381)``
`3878fe6fab <https://github.com/apache/airflow/commit/3878fe6fab3ccc1461932b456c48996f2763139f>`_  2023-07-05   ``Remove spurious headers for provider changelogs (#32373)``
`cb4927a018 <https://github.com/apache/airflow/commit/cb4927a01887e2413c45d8d9cb63e74aa994ee74>`_  2023-07-05   ``Prepare docs for July 2023 wave of Providers (#32298)``
`f8593503cb <https://github.com/apache/airflow/commit/f8593503cbe252c2f4dc5ff48a3f292c9e13baad>`_  2023-07-05   ``Add default_deferrable config (#31712)``
`d6e254db68 <https://github.com/apache/airflow/commit/d6e254db689db070f2f181006e7d6bc593482300>`_  2023-06-30   ``Deprecate 'delimiter' param and source object's wildcards in GCS, introduce 'match_glob' param. (#31261)``
`dd937e51fe <https://github.com/apache/airflow/commit/dd937e51fe1ae3cd36a6993bd42e425960644e1d>`_  2023-06-30   ``Add 'on_finish_action' to 'KubernetesPodOperator' (#30718)``
`c0eaa9b25d <https://github.com/apache/airflow/commit/c0eaa9b25d11eeb6fba1b716323c4ff2c2dbd5e1>`_  2023-06-29   ``Add deferrable mode to CloudSQLExportInstanceOperator (#30852)``
`f3f69bf1e0 <https://github.com/apache/airflow/commit/f3f69bf1e0c025d260be91daada04476d2418e9d>`_  2023-06-29   ``Refactor GKECreateClusterOperator's body validation (#31923)``
`7d2ec76c72 <https://github.com/apache/airflow/commit/7d2ec76c72f70259b67af0047aa785b28668b411>`_  2023-06-29   ``Make the deferrable version of DataprocCreateBatchOperator handle a batch_id that already exists (#32216)``
`09d4718d3a <https://github.com/apache/airflow/commit/09d4718d3a46aecf3355d14d3d23022002f4a818>`_  2023-06-27   ``Improve provider documentation and README structure (#32125)``
`b156db3a70 <https://github.com/apache/airflow/commit/b156db3a70cca5b3d231c0c49f013fbd0af5d194>`_  2023-06-23   ``Adding 'src_fmt_configs' to the list of template fields. (#32097)``
`59d64d8f2e <https://github.com/apache/airflow/commit/59d64d8f2ed3c0e7b93d3c07041d47883cabb908>`_  2023-06-22   ``[Issue-32069] Fix name format in the batch requests (#32070)``
`fd116cc196 <https://github.com/apache/airflow/commit/fd116cc1964c49e21aaac6062fff596764833c59>`_  2023-06-22   ``Google provider docstring improvements (#31731)``
`8f41584777 <https://github.com/apache/airflow/commit/8f41584777d5121b5323cc14f7c29f5ebaf736fb>`_  2023-06-21   ``Optimize deferrable mode execution for 'BigQueryValueCheckOperator' (#31872)``
`fe7a1aa096 <https://github.com/apache/airflow/commit/fe7a1aa0962538a99f5e73dbd3890a6f210d22ed>`_  2023-06-21   ``Switch Google Ads API version from v13 to v14 (#32028)``
`43fa157e51 <https://github.com/apache/airflow/commit/43fa157e51ac6abe6de8475c7fd356507f453d8f>`_  2023-06-20   ``Fix 'BigQueryInsertJobOperator'  error handling in deferrable mode (#32034)``
`2a79fb74fd <https://github.com/apache/airflow/commit/2a79fb74fd7203fe82b9384af42a59b3a41f84e9>`_  2023-06-20   ``Fix 'BIGQUERY_JOB_DETAILS_LINK_FMT' in 'BigQueryConsoleLink' (#31953)``
=================================================================================================  ===========  =============================================================================================================

10.2.0
......

Latest change: 2023-06-20

=================================================================================================  ===========  ========================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ========================================================================================================
`79bcc2e668 <https://github.com/apache/airflow/commit/79bcc2e668e648098aad6eaa87fe8823c76bc69a>`_  2023-06-20   ``Prepare RC1 docs for June 2023 wave of Providers (#32001)``
`8b146152d6 <https://github.com/apache/airflow/commit/8b146152d62118defb3004c997c89c99348ef948>`_  2023-06-20   ``Add note about dropping Python 3.7 for providers (#32015)``
`f2ebc292fe <https://github.com/apache/airflow/commit/f2ebc292fe63d2ddd0686d90c3acc0630f017a07>`_  2023-06-19   ``Provide missing project id and creds for TabularDataset (#31991)``
`66299338eb <https://github.com/apache/airflow/commit/66299338eb24aa71eb2e27ebd8b76079b39fd305>`_  2023-06-18   ``add a return when the event is yielded in a loop to stop the execution (#31985)``
`e6960f1ad6 <https://github.com/apache/airflow/commit/e6960f1ad63f40ff4ccde6c86b17e051b302c104>`_  2023-06-15   ``Revert "Fix 'BIGQUERY_JOB_DETAILS_LINK_FMT' in 'BigQueryConsoleLink' (#31457)" (#31935)``
`c7072c0490 <https://github.com/apache/airflow/commit/c7072c0490cb80b448622a27eb1056576d6b92a4>`_  2023-06-15   ``Fix 'BIGQUERY_JOB_DETAILS_LINK_FMT' in 'BigQueryConsoleLink' (#31457)``
`a81ac70b33 <https://github.com/apache/airflow/commit/a81ac70b33a589c58b59864df931d3293fada382>`_  2023-06-15   ``Add deferrable mode to PubsubPullSensor (#31284)``
`b502e665d6 <https://github.com/apache/airflow/commit/b502e665d633262f3ce52d9c002c0a25e6e4ec9d>`_  2023-06-14   ``Add a new param to set parquet row group size in 'BaseSQLToGCSOperator' (#31831)``
`810d46776a <https://github.com/apache/airflow/commit/810d46776ad1a52f27ec578e5be875c39c90fc45>`_  2023-06-11   ``Implement MetastoreHivePartitionSensor (#31016)``
`233663046d <https://github.com/apache/airflow/commit/233663046d5210359ce9f4db2fe3db4f5c38f6ee>`_  2023-06-08   ``Add 'cacheControl' field to google cloud storage (#31338)``
`ba3665f76a <https://github.com/apache/airflow/commit/ba3665f76a2205bad4553ba00537026a1346e9ae>`_  2023-06-08   ``Bigquery: fix links for already existing tables and datasets. (#31589)``
`fbeb01cb17 <https://github.com/apache/airflow/commit/fbeb01cb17b7cb9c2e27ac7010f423a2bced78b4>`_  2023-06-07   ``Replace unicodecsv with standard csv library (#31693)``
`d91861d3bd <https://github.com/apache/airflow/commit/d91861d3bdbde18c937978c878d137d6c758e2c6>`_  2023-06-07   ``Optimize deferrable mode (#31758)``
`9e268e13b1 <https://github.com/apache/airflow/commit/9e268e13b147401a5665e497aee87ac107ade8d1>`_  2023-06-07   ``Replace spelling directive with spelling:word-list (#31752)``
`36ffbee4aa <https://github.com/apache/airflow/commit/36ffbee4aae37b83b188d35aedd36add8dedf50e>`_  2023-06-05   ``Add D400 pydocstyle check - Google provider only (#31422)``
`495ae23d45 <https://github.com/apache/airflow/commit/495ae23d45eda52f2b368d0afa4213f4e69e97cd>`_  2023-06-05   ``Optimize deferrable mode execution for 'DataprocSubmitJobOperator' (#31317)``
`86b5ba2802 <https://github.com/apache/airflow/commit/86b5ba28026fc6e8b7d868b83080189df9b09306>`_  2023-06-04   ``Remove return statement after yield from triggers class (#31703)``
`dc5bf3fd02 <https://github.com/apache/airflow/commit/dc5bf3fd02c589578209cb0dd5b7d005b1516ae9>`_  2023-06-02   ``Add discoverability for triggers in provider.yaml (#31576)``
`47c2023df2 <https://github.com/apache/airflow/commit/47c2023df273654bb6ea4b1ec08ab86dfb633092>`_  2023-05-31   ``Add 'preserveAsciiControlCharacters' to 'src_fmt_configs' (#31643)``
`e3ec1ac72e <https://github.com/apache/airflow/commit/e3ec1ac72eac9aa6a9f3a99154fe0bf53a8d283a>`_  2023-05-30   ``Add support for credential configuation file auth to Google Secrets Manager secrets backend (#31597)``
`9fa75aaf7a <https://github.com/apache/airflow/commit/9fa75aaf7a391ebf0e6b6949445c060f6de2ceb9>`_  2023-05-29   ``Remove Python 3.7 support (#30963)``
`ef40148170 <https://github.com/apache/airflow/commit/ef40148170ce1110a4c9a859207d40dcc6ad1cd5>`_  2023-05-26   ``Add credential configuration file support to Google Cloud Hook (#31548)``
`22e44ab9f2 <https://github.com/apache/airflow/commit/22e44ab9f2f3a68aa2ed236cfe514554dd479a38>`_  2023-05-26   ``FIPS environments: Mark uses of md5 as "not-used-for-security" (#31171)``
`5ae9728db7 <https://github.com/apache/airflow/commit/5ae9728db7d34d287907ca3a919ac1a94c776799>`_  2023-05-25   ``Add deferrable mode to 'GCSUploadSessionCompleteSensor' (#31081)``
`28f2e70916 <https://github.com/apache/airflow/commit/28f2e709165a56f0bc1097d7457149330914cea9>`_  2023-05-25   ``Optimize deferrable mode execution for 'BigQueryInsertJobOperator' (#31249)``
`769e204d53 <https://github.com/apache/airflow/commit/769e204d533769a50f4b40b9f6cfe718960877df>`_  2023-05-24   ``Add append_job_name parameter in DataflowStartFlexTemplateOperator (#31511)``
=================================================================================================  ===========  ========================================================================================================

10.1.1
......

Latest change: 2023-05-24

=================================================================================================  ===========  ==============================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==============================================================================================
`d745cee3db <https://github.com/apache/airflow/commit/d745cee3dbde6b437a817aa64e385a1a948389d5>`_  2023-05-24   ``Prepare adhoc wave of Providers (#31478)``
`c082aec089 <https://github.com/apache/airflow/commit/c082aec089405ed0399cfee548011b0520be0011>`_  2023-05-23   ``Fix accessing a GKE cluster through the private endpoint in 'GKEStartPodOperator' (#31391)``
`0d6e626b05 <https://github.com/apache/airflow/commit/0d6e626b050a860462224ad64dc5e9831fe8624d>`_  2023-05-22   ``Fix 'BigQueryGetDataOperator''s query job bugs in deferrable mode (#31433)``
=================================================================================================  ===========  ==============================================================================================

10.1.0
......

Latest change: 2023-05-19

=================================================================================================  ===========  ===========================================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ===========================================================================================================================
`45548b9451 <https://github.com/apache/airflow/commit/45548b9451fba4e48c6f0c0ba6050482c2ea2956>`_  2023-05-19   ``Prepare RC2 docs for May 2023 wave of Providers (#31416)``
`54f1fb0574 <https://github.com/apache/airflow/commit/54f1fb0574a6ecf8f415bbf6da1aaf6f1999bb29>`_  2023-05-19   ``Docstring improvements (#31375)``
`cfe759dc59 <https://github.com/apache/airflow/commit/cfe759dc59bfc3390e7ba07184f0de9eb725122d>`_  2023-05-19   ``Switch default Google ads to v13 (#31382)``
`abea189022 <https://github.com/apache/airflow/commit/abea18902257c0250fedb764edda462f9e5abc84>`_  2023-05-18   ``Use '__version__' in providers not 'version' (#31393)``
`db8cbf6ab5 <https://github.com/apache/airflow/commit/db8cbf6ab5e144f58555e0c30361d8d6ec31ef21>`_  2023-05-18   ``Add get_namespace to GKEPodHook (#31397)``
`f5aed58d9f <https://github.com/apache/airflow/commit/f5aed58d9fb2137fa5f0e3ce75b6709bf8393a94>`_  2023-05-18   ``Fixing circular import error in providers caused by airflow version check (#31379)``
`d677a263be <https://github.com/apache/airflow/commit/d677a263be0a55fcbbb905f7f47b67bf0f77f59d>`_  2023-05-18   ``Switch to google ads v13 (#31369)``
`28d1bf8dfc <https://github.com/apache/airflow/commit/28d1bf8dfc03787cc2b4373bbaa27527bdd91846>`_  2023-05-18   ``Update SDKs for google provider package (#30067)``
`d9ff55cf6d <https://github.com/apache/airflow/commit/d9ff55cf6d95bb342fed7a87613db7b9e7c8dd0f>`_  2023-05-16   ``Prepare docs for May 2023 wave of Providers (#31252)``
`cf1e26b046 <https://github.com/apache/airflow/commit/cf1e26b04669ad2b232618fee623e6bc7797a13a>`_  2023-05-16   ``Add BigQueryToPostgresOperator (#30658)``
`d9f70dffd1 <https://github.com/apache/airflow/commit/d9f70dffd1813fa6356d8981167eca6d5f317bb1>`_  2023-05-16   ``Add CloudBuild build id log (#30516)``
`caeca2d143 <https://github.com/apache/airflow/commit/caeca2d143152ef037ccbaae858f1e2fa6763674>`_  2023-05-15   ``Add protocol to define methods relied upon by KubernetesPodOperator (#31298)``
`d3a2dbe028 <https://github.com/apache/airflow/commit/d3a2dbe028e4a8c2da9fcb2b3257e2117c413a73>`_  2023-05-15   ``GKEPodHook needs to have all methods KPO calls (#31266)``
`fb6c501124 <https://github.com/apache/airflow/commit/fb6c501124186f695b9dfa497cde10298ac12e9f>`_  2023-05-13   ``Add flag apply_gcs_prefix to S3ToGCSOperator (b/245077385) (#31127)``
`a66edcbb2c <https://github.com/apache/airflow/commit/a66edcbb2c9c04031326a3965c76a419043338ff>`_  2023-05-13   ``'CreateBatchPredictionJobOperator' Add batch_size param for Vertex AI BatchPredictionJob objects (#31118)``
`d1fe67184d <https://github.com/apache/airflow/commit/d1fe67184da26fb0bca2416e26f321747fa4aa5d>`_  2023-05-12   ``Add 'use_legacy_sql' param to 'BigQueryGetDataOperator' (#31190)``
`b8f73768ec <https://github.com/apache/airflow/commit/b8f73768ec13f8d4cc1605cca3fa93be6caac473>`_  2023-05-09   ``Add 'as_dict' param to 'BigQueryGetDataOperator' (#30887)``
`e68d4a7764 <https://github.com/apache/airflow/commit/e68d4a77645a5f0c199d5618912a99be71281920>`_  2023-05-08   ``implement gcs_schema_object for BigQueryCreateExternalTableOperator (#30961)``
`810b5d4da4 <https://github.com/apache/airflow/commit/810b5d4da4396cedcd483d20e50873c2b81cf5ad>`_  2023-05-08   ``'DataflowTemplatedJobStartOperator' fix overwriting of location with default value, when a region is provided. (#31082)``
`ac46902154 <https://github.com/apache/airflow/commit/ac46902154c060246dec942f921f7670015e6031>`_  2023-05-04   ``Move TaskInstanceKey to a separate file (#31033)``
`0a30706aa7 <https://github.com/apache/airflow/commit/0a30706aa7c581905ca99a8b6e2f05960d480729>`_  2023-05-03   ``Use 'AirflowProviderDeprecationWarning' in providers (#30975)``
`eef5bc7f16 <https://github.com/apache/airflow/commit/eef5bc7f166dc357fea0cc592d39714b1a5e3c14>`_  2023-05-03   ``Add full automation for min Airflow version for providers (#30994)``
`b0a40bb812 <https://github.com/apache/airflow/commit/b0a40bb8129aeddd3e7ed78417c64406ebb50063>`_  2023-04-30   ``Optimize deferred execution mode (#30946)``
`a7eb32a5b2 <https://github.com/apache/airflow/commit/a7eb32a5b222e236454d3e474eec478ded7c368d>`_  2023-04-30   ``Bump minimum Airflow version in providers (#30917)``
`f89d7b9848 <https://github.com/apache/airflow/commit/f89d7b98487d993387ebea4af526fe20204ce02a>`_  2023-04-28   ``Poke once before defer for GCSObjectsWithPrefixExistenceSensor (#30939)``
`a3741e0e02 <https://github.com/apache/airflow/commit/a3741e0e0216bacbd18d7dc9d83c9370af82a665>`_  2023-04-28   ``Optimize deferrable mode execution (#30920)``
`0d95acef1d <https://github.com/apache/airflow/commit/0d95acef1d0d47fd95545645a75e64fe7c4bb6a6>`_  2023-04-28   ``Add deferrable mode to DataprocInstantiateInlineWorkflowTemplateOperator (#30878)``
`3a5b583c91 <https://github.com/apache/airflow/commit/3a5b583c916fff4603cdb2f2be815ccc5c281750>`_  2023-04-27   ``Optimize deferrable mode in 'GCSObjectExistenceSensor' (#30901)``
`eed5d5b7cc <https://github.com/apache/airflow/commit/eed5d5b7cc8b95a7e7ab0ac5f92c1d3a173dfc75>`_  2023-04-27   ``Add deferrable mode to 'GCSObjectsWithPrefixExistenceSensor' (#30618)``
`48c9625c70 <https://github.com/apache/airflow/commit/48c9625c700e20f03fcddf97d41cbd749058b053>`_  2023-04-24   ``Add 'priority' parameter to BigQueryHook (#30655)``
`9409446097 <https://github.com/apache/airflow/commit/940944609751e2584b191aa776b6221aa78703d3>`_  2023-04-24   ``Add cli cmd to list the provider trigger info (#30822)``
`432697d90c <https://github.com/apache/airflow/commit/432697d90cdcea35607bcaa970c694c88053222c>`_  2023-04-23   ``allow multiple prefixes in gcs delete/list hooks and operators (#30815)``
`c499b6beb2 <https://github.com/apache/airflow/commit/c499b6beb20737addc03aa4266d61f10f660c2b8>`_  2023-04-22   ``Small refactors in ClusterGenerator of dataproc (#30714)``
`c585ad51c5 <https://github.com/apache/airflow/commit/c585ad51c522c6e9f3bbbf7ae6e0132e25a3a378>`_  2023-04-22   ``Upgrade ruff to 0.0.262 (#30809)``
`676a95b220 <https://github.com/apache/airflow/commit/676a95b2207e4eb97403bbe78b35716538901b8e>`_  2023-04-22   ``Fix removed delegate_to parameter in deferrable GCS sensor (#30810)``
`9e49d91a0a <https://github.com/apache/airflow/commit/9e49d91a0a9462696d9b3cebc55275e704943fbf>`_  2023-04-22   ``Add deferrable mode to 'GCSObjectUpdateSensor' (#30579)``
=================================================================================================  ===========  ===========================================================================================================================

10.0.0
......

Latest change: 2023-04-21

=================================================================================================  ===========  ====================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ====================================================================================
`e46ce78b66 <https://github.com/apache/airflow/commit/e46ce78b66953146c04de5da00cab6299787adad>`_  2023-04-21   ``Prepare docs for adhoc release of providers (#30787)``
`fbc1382514 <https://github.com/apache/airflow/commit/fbc13825140cc6cc6b3d4b27db6d329692a1c451>`_  2023-04-21   ``remove delegate_to from GCP operators and hooks (#30748)``
`b48f959ae9 <https://github.com/apache/airflow/commit/b48f959ae93703f52721999ef04f459fe56dcf58>`_  2023-04-21   ``Update DataprocCreateCluster operator to use 'label' parameter properly (#30741)``
`da2749cae5 <https://github.com/apache/airflow/commit/da2749cae56d6e0da322695b3286acd9393052c8>`_  2023-04-15   ``Update Google Campaign Manager360 operators to use API v4 (#30598)``
`4eab616e9f <https://github.com/apache/airflow/commit/4eab616e9f0a89c1a6268d5b5eaba526bfa9be6d>`_  2023-04-15   ``add missing project_id in BigQueryGetDataOperator (#30651)``
`57c09e59ee <https://github.com/apache/airflow/commit/57c09e59ee9273ff64cd4a85b020a4df9b1d9eca>`_  2023-04-14   ``Display Video 360 cleanup v1 API usage (#30577)``
=================================================================================================  ===========  ====================================================================================

9.0.0
.....

Latest change: 2023-04-12

=================================================================================================  ===========  =========================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =========================================================================
`0f3b6579cb <https://github.com/apache/airflow/commit/0f3b6579cb67d3cf8bd9fa8f9abd502fc774201a>`_  2023-04-12   ``Prepare docs for RC2 of provider wave (#30606)``
`874ea9588e <https://github.com/apache/airflow/commit/874ea9588e3ce7869759440302e53bb6a730a11e>`_  2023-04-09   ``Prepare docs for ad hoc release of Providers (#30545)``
`71db47a73d <https://github.com/apache/airflow/commit/71db47a73d741015d8ffeaa2276635f19d51f8e7>`_  2023-04-09   ``Update DV360 operators to use API v2 (#30326)``
`3d2c96e3f5 <https://github.com/apache/airflow/commit/3d2c96e3f5d238955bccba190726d0fba860eb7a>`_  2023-04-08   ``Add deferrable mode to GKEStartPodOperator (#29266)``
`4703f9a0e5 <https://github.com/apache/airflow/commit/4703f9a0e589557f5176a6f466ae83fe52644cf6>`_  2023-04-08   ``BigQueryHook list_rows/get_datasets_list can return iterator (#30543)``
`d9896fd96e <https://github.com/apache/airflow/commit/d9896fd96eb91a684a512a86924a801db53eb945>`_  2023-04-08   ``Fix dynamic imports in google ads vendored in library (#30544)``
`d23a3bbed8 <https://github.com/apache/airflow/commit/d23a3bbed89ae04369983f21455bf85ccc1ae1cb>`_  2023-04-04   ``Add mechanism to suspend providers (#30422)``
`2ba1e63c37 <https://github.com/apache/airflow/commit/2ba1e63c37d56a4bba6f69c07497112a5e7cb157>`_  2023-04-04   ``Fix cloud build async credentials (#30441)``
`cc6fd5c0d9 <https://github.com/apache/airflow/commit/cc6fd5c0d915e7f77feff70fef23519515b12083>`_  2023-04-03   ``Small quotation fix (#30448)``
=================================================================================================  ===========  =========================================================================

8.12.0
......

Latest change: 2023-04-02

=================================================================================================  ===========  ========================================================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ========================================================================================================================================
`55dbf1ff1f <https://github.com/apache/airflow/commit/55dbf1ff1fb0b22714f695a66f6108b3249d1199>`_  2023-04-02   ``Prepare docs for April 2023 wave of Providers (#30378)``
`25048fa6b2 <https://github.com/apache/airflow/commit/25048fa6b21b1e75a0c6fb6d626c67860e8cecff>`_  2023-04-01   ``Switch to using vendored-in google ads. (#30410)``
`2e65c70e99 <https://github.com/apache/airflow/commit/2e65c70e99e73d4bc39e26da88f9e0102dd41f65>`_  2023-04-01   ``Merging of the google ads vendored-in code. (#30399)``
`540a076801 <https://github.com/apache/airflow/commit/540a0768012c82794add3ec159768521e01a0fe2>`_  2023-03-30   ``merge BigQueryTableExistenceAsyncSensor into BigQueryTableExistenceSensor (#30235)``
`29eba167ea <https://github.com/apache/airflow/commit/29eba167eac5d08862a85dd1358a8b6c43f61200>`_  2023-03-22   ``Merge BigQueryTableExistencePartitionAsyncSensor into BigQueryTableExistencePartitionSensor (#30231)``
`79a2fa7db9 <https://github.com/apache/airflow/commit/79a2fa7db9d1689c5fe8a0afaa3883c4e0ccc00d>`_  2023-03-21   ``Merge GCSObjectExistenceAsyncSensor logic to GCSObjectExistenceSensor (#30014)``
`af4627fec9 <https://github.com/apache/airflow/commit/af4627fec988995537de7fa172875497608ef710>`_  2023-03-20   ``fix setting project_id for gs to bq and bq to gs (#30053)``
`75fd5e8c54 <https://github.com/apache/airflow/commit/75fd5e8c54cdc0465ed43c9b36b3d0672bd7e059>`_  2023-03-16   ``Add missing 'poll_interval' in Bigquery operator (#30132)``
`5a3be7256b <https://github.com/apache/airflow/commit/5a3be7256b2a848524d3635d7907b6829a583101>`_  2023-03-15   ``Handling project location param on async BigQuery dts trigger (#29786)``
`a6715805c7 <https://github.com/apache/airflow/commit/a6715805c7e4694e85b8f3ebff162a2c3905110e>`_  2023-03-14   ``Add poll_interval param in BigQueryInsertJobOperator (#30091)``
`57fb80cff0 <https://github.com/apache/airflow/commit/57fb80cff020a3e405c7d6a72037a7757ccdd5f5>`_  2023-03-14   ``Support CloudDataTransferServiceJobStatusSensor without specifying a project_id (#30035)``
`def1f89e70 <https://github.com/apache/airflow/commit/def1f89e702d401f67a94f34a01f6a4806ea92e6>`_  2023-03-10   ``Fix location on cloud build operators (#29937)``
`599c587e26 <https://github.com/apache/airflow/commit/599c587e26d5e0b8fa0a0967f3dc4fa92d257ed0>`_  2023-03-10   ``Add 'job_id' to 'BigQueryToGCSOperator' templated_fields (#30006)``
`c3867781e0 <https://github.com/apache/airflow/commit/c3867781e09b7e0e0d19c0991865a2453194d9a8>`_  2023-03-08   ``adding trigger info to provider yaml (#29950)``
`b6392ae5fd <https://github.com/apache/airflow/commit/b6392ae5fd466fa06ca92c061a0f93272e27a26b>`_  2023-03-07   ``Support deleting the local log files when using remote logging (#29772)``
`464ab1b7ca <https://github.com/apache/airflow/commit/464ab1b7caa78637975008fcbb049d5b52a8b005>`_  2023-03-05   ``Wait insert_job result in normal mode (#29925)``
`f55b9576b1 <https://github.com/apache/airflow/commit/f55b9576b1363d2cada0a25daf79501c8aad8b54>`_  2023-03-05   ``'GoogleDriveHook': Fixing log message + adding more verbose documentation (#29694)``
`035ad26d79 <https://github.com/apache/airflow/commit/035ad26d79848c63049307a94c04a9a3916d8a38>`_  2023-03-04   ``Add "BOOLEAN" to type_map of MSSQLToGCSOperator, fix incorrect bit->int type conversion by specifying BIT fields explicitly (#29902)``
`5a632f78eb <https://github.com/apache/airflow/commit/5a632f78eb6e3dcd9dc808e73b74581806653a89>`_  2023-03-04   ``Google Cloud Providers - Fix _MethodDefault deepcopy failure (#29518)``
`971039454a <https://github.com/apache/airflow/commit/971039454a3684d0ea7261dfe91f34ac4b62af72>`_  2023-03-04   ``Align cncf provider file names with AIP-21 (#29905)``
`864ff2e3ce <https://github.com/apache/airflow/commit/864ff2e3ce185dfa3df0509a4bd3c6b5169e907f>`_  2023-03-04   ``Remove  unnecessary upper constraints from google provider (#29915)``
=================================================================================================  ===========  ========================================================================================================================================

8.11.0
......

Latest change: 2023-03-03

=================================================================================================  ===========  ======================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ======================================================================================================
`fcd3c0149f <https://github.com/apache/airflow/commit/fcd3c0149f17b364dfb94c0523d23e3145976bbe>`_  2023-03-03   ``Prepare docs for 03/2023 wave of Providers (#29878)``
`3fc9461654 <https://github.com/apache/airflow/commit/3fc946165458f203162ddb229bee133e1a6fcac2>`_  2023-03-03   ``Add 'CloudSQLCloneInstanceOperator' (#29726)``
`47ab0ca629 <https://github.com/apache/airflow/commit/47ab0ca6295f301d393dbb29e134fa90be0ad7df>`_  2023-03-03   ``Move help message to the google auth code (#29888)``
`972fca2253 <https://github.com/apache/airflow/commit/972fca22532121493d49753bd6d8388af5943689>`_  2023-02-28   ``Fix 'NoneType' object is not subscriptable. (#29820)``
`ec844eaa0a <https://github.com/apache/airflow/commit/ec844eaa0a3864d1da74d9ee6c3cf7edb36fbe8c>`_  2023-02-27   ``Add deferrable mode to BigQueryTablePartitionExistenceSensor. (#29735)``
`a5adb87ab4 <https://github.com/apache/airflow/commit/a5adb87ab4ee537eb37ef31aba755b40f6f29a1e>`_  2023-02-26   ``Add a new param for BigQuery operators to support additional actions when resource exists (#29394)``
`1e7c064560 <https://github.com/apache/airflow/commit/1e7c064560b8504b45e3a53dc8f294b143b4ec7d>`_  2023-02-25   ``Google Cloud Providers - Introduce GoogleCloudBaseOperator (#29680)``
`ad08f66228 <https://github.com/apache/airflow/commit/ad08f662280612f44549a71f9c835595cfd05f0a>`_  2023-02-22   ``Remove <2.0.0 limit on google-cloud-bigtable (#29644)``
`dba390e323 <https://github.com/apache/airflow/commit/dba390e32330675e1b94442c8001ea980754c189>`_  2023-02-22   ``Fix and augment 'check-for-inclusive-language' CI check (#29549)``
`f51742d20b <https://github.com/apache/airflow/commit/f51742d20b2e53bcd90a19db21e4e12d2a287677>`_  2023-02-21   ``Don't push secret in XCOM in BigQueryCreateDataTransferOperator (#29348)``
`3dbcf99d20 <https://github.com/apache/airflow/commit/3dbcf99d20d47cde0debdd5faf9bd9b2ebde1718>`_  2023-02-21   ``Update google cloud dlp package and adjust hook and operators (#29234)``
`6ef5ba9104 <https://github.com/apache/airflow/commit/6ef5ba9104f5a658b003f8ade274f19d7ec1b6a9>`_  2023-02-20   ``Refactor Dataproc Trigger (#29364)``
`7e3a9fc858 <https://github.com/apache/airflow/commit/7e3a9fc8586d0e6d9eddbf833a75280e68050da8>`_  2023-02-20   ``Dataproc batches (#29136)``
`1677d80e65 <https://github.com/apache/airflow/commit/1677d80e6573acfc7a706ac25c4ee3a353071f7b>`_  2023-02-20   ``Add deferrable mode to DataprocInstantiateWorkflowTemplateOperator (#28618)``
=================================================================================================  ===========  ======================================================================================================

8.10.0
......

Latest change: 2023-02-18

=================================================================================================  ===========  ====================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ====================================================================================
`470fdaea27 <https://github.com/apache/airflow/commit/470fdaea275660970777c0f72b8867b382eabc14>`_  2023-02-18   ``Prepare docs for 02 2023 midmonth wave of Providers (#29589)``
`f37772adfd <https://github.com/apache/airflow/commit/f37772adfdfdee8763147e0563897e4d5d5657c8>`_  2023-02-18   ``'GoogleDriveHook': Add folder_id param to upload_file (#29477)``
`28126c12fb <https://github.com/apache/airflow/commit/28126c12fbdd2cac84e0fbcf2212154085aa5ed9>`_  2023-02-14   ``Add defer mode to GKECreateClusterOperator and GKEDeleteClusterOperator (#28406)``
`32c571e592 <https://github.com/apache/airflow/commit/32c571e5926983903ac8b9017c36f14137a797a5>`_  2023-02-14   ``Move cloud_sql_binary_path from connection to Hook (#29499)``
`41fade2d21 <https://github.com/apache/airflow/commit/41fade2d219c1841fafa439cc5dbb036f34ee32a>`_  2023-02-13   ``Upgrade Mypy to 1.0 (#29468)``
`5e6f8eb4d5 <https://github.com/apache/airflow/commit/5e6f8eb4d5fdcaa713022ee46b1ca9bd2e3ab44e>`_  2023-02-13   ``Check that cloud sql provider version is valid (#29497)``
`f9e9d23457 <https://github.com/apache/airflow/commit/f9e9d23457cba5d3e18b5bdb7b65ecc63735b65b>`_  2023-02-11   ``Restore trigger logging (#29482)``
`7ee1a56244 <https://github.com/apache/airflow/commit/7ee1a5624497fc457af239e93e4c1af94972bbe6>`_  2023-02-11   ``Add documentation for BigQuery transfer operators (#29466)``
`60d4bcd1d1 <https://github.com/apache/airflow/commit/60d4bcd1d101bb56955081d14e3e138a0c960c5f>`_  2023-02-10   ``Revert "Enable individual trigger logging (#27758)" (#29472)``
`6c1eeb5839 <https://github.com/apache/airflow/commit/6c1eeb58393173895944d5414793b38abdc7510d>`_  2023-02-11   ``Revert "Upgrade mypy to 0.991 (#28926)" (#29470)``
`6ae0a80cba <https://github.com/apache/airflow/commit/6ae0a80cbaf1d33343b763c7f82612b4522afc40>`_  2023-02-11   ``Upgrade mypy to 0.991 (#28926)``
=================================================================================================  ===========  ====================================================================================

8.9.0
.....

Latest change: 2023-02-08

=================================================================================================  ===========  ===================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ===================================================================================================
`ce6ae2457e <https://github.com/apache/airflow/commit/ce6ae2457ef3d9f44f0086b58026909170bbf22a>`_  2023-02-08   ``Prepare docs for Feb 2023 wave of Providers (#29379)``
`1b18a501fe <https://github.com/apache/airflow/commit/1b18a501fe818079e535838fa4f232b03365fc75>`_  2023-02-03   ``Enable individual trigger logging (#27758)``
`872df121e2 <https://github.com/apache/airflow/commit/872df121e2ae24520eeb29fe606183a566e35dd8>`_  2023-02-03   ``Add deferrable capability to existing ''DataprocDeleteClusterOperator'' (#29349)``
`094d6bf01b <https://github.com/apache/airflow/commit/094d6bf01b9d8b1a5d358dc10fd561cf3a04c51b>`_  2023-01-30   ``Add deferrable mode to dataflow operators (#27776)``
`9d9351728c <https://github.com/apache/airflow/commit/9d9351728cac9f9ed3bea0504dcfa8da15a7461b>`_  2023-01-30   ``Add deferrable mode to DataprocCreateBatchOperator (#28457)``
`9fd80130e2 <https://github.com/apache/airflow/commit/9fd80130e2351c7ec31bbeb6c10f6b11708b318b>`_  2023-01-25   ``Add deferrable mode to DataprocCreateClusterOperator and DataprocUpdateClusterOperator (#28529)``
`02bebf897b <https://github.com/apache/airflow/commit/02bebf897b5a7d166f8cc9304eb58290aea1eba6>`_  2023-01-25   ``Add deferrable mode to MLEngineStartTrainingJobOperator (#27405)``
`cf90a1a567 <https://github.com/apache/airflow/commit/cf90a1a5673d4c7a72b7209439eca6c03b07b99a>`_  2023-01-25   ``Keyfile dict can be dict not str (#29135)``
`b4c50dadd3 <https://github.com/apache/airflow/commit/b4c50dadd36d66e4d222c627a61771653767afd6>`_  2023-01-24   ``GCSTaskHandler may use remote log conn id (#29117)``
`b2825e1185 <https://github.com/apache/airflow/commit/b2825e11852890cf0b0f4d0bcaae592311781cdf>`_  2023-01-24   ``Fix GoogleDriveHook writing files to trashed folders on upload v2 (#29119)``
`be0e35321f <https://github.com/apache/airflow/commit/be0e35321f0bbd7d21c75096cad45dbe20c2359a>`_  2023-01-24   ``fix Google provider CHANGELOG.rst (#29122)``
`3374fdfcbd <https://github.com/apache/airflow/commit/3374fdfcbddb630b4fc70ceedd5aed673e6c0a0d>`_  2023-01-23   ``Deprecate 'delegate_to' param in GCP operators and update docs (#29088)``
`7e2493e3c8 <https://github.com/apache/airflow/commit/7e2493e3c8b2dbeb378dba4e40110ab1e4ad24da>`_  2023-01-23   ``fix Google provider CHANGELOG.rst (#29114)``
`90e6277da6 <https://github.com/apache/airflow/commit/90e6277da6b4102cf565134739af10bafa9d3894>`_  2023-01-23   ``Auto ML assets (#25466)``
`e926bb9bb0 <https://github.com/apache/airflow/commit/e926bb9bb0ce97b4bb32e49279bde237ba8935ed>`_  2023-01-20   ``Add deferrable mode to DataFusionStartPipelineOperator (#28690)``
`5fcdd321c5 <https://github.com/apache/airflow/commit/5fcdd321c5b9f220991af4c552401c8dd00fbffe>`_  2023-01-20   ``Add deferrable mode for Big Query Transfer operator (#27833)``
`5350be2194 <https://github.com/apache/airflow/commit/5350be2194250366536db7f78b88dc8e49c9620e>`_  2023-01-19   ``Add support for write_on_empty in BaseSQLToGCSOperator (#28959)``
`dc3a3c7c52 <https://github.com/apache/airflow/commit/dc3a3c7c52aab815ddd49b33aba4e6040d8512af>`_  2023-01-16   ``Add DataprocCancelOperationOperator (#28456)``
=================================================================================================  ===========  ===================================================================================================

8.8.0
.....

Latest change: 2023-01-14

=================================================================================================  ===========  =========================================================================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =========================================================================================================================================================
`911b708ffd <https://github.com/apache/airflow/commit/911b708ffddd4e7cb6aaeac84048291891eb0f1f>`_  2023-01-14   ``Prepare docs for Jan 2023 mid-month wave of Providers (#28929)``
`ce858a5d71 <https://github.com/apache/airflow/commit/ce858a5d719fb1dff85ad7e4747f0777404d1f56>`_  2023-01-12   ``Switch to ruff for faster static checks (#28893)``
`f1eb2f1af4 <https://github.com/apache/airflow/commit/f1eb2f1af42c537f7c49a891f238083fd5d9e762>`_  2023-01-12   ``'BigQueryCreateExternalTableOperator' fix field delimiter not working with csv (#28856)``
`a337e6209a <https://github.com/apache/airflow/commit/a337e6209ad1ded42db3f1d788c3f4df4f1d645a>`_  2023-01-11   ``Fix using private _get_credentials instead of public get_credentials (#28588)``
`284cd52989 <https://github.com/apache/airflow/commit/284cd529898fbadd14308004a0b0cb6f389b4318>`_  2023-01-10   ``Add deferrable ''GCSObjectExistenceSensorAsync'' (#28763)``
`35a8ffc55a <https://github.com/apache/airflow/commit/35a8ffc55af220b16ea345d770f80f698dcae3fb>`_  2023-01-10   ``Support partition_columns in BaseSQLToGCSOperator (#28677)``
`c0b2fcff24 <https://github.com/apache/airflow/commit/c0b2fcff24184aa0c5beb9c0d06ce7d67b5c5b7e>`_  2023-01-09   ``assign "datasetReference" attribute to dataset_reference dict. by default if not already set in create_empty_dataset method of bigquery hook (#28782)``
`71306b31f1 <https://github.com/apache/airflow/commit/71306b31f1842ee2b1eb1cc2980b90f0fb6b11dc>`_  2023-01-09   ``Fix'GoogleCampaignManagerReportSensor' with 'QUEUED' status (#28735)``
`c67f4af667 <https://github.com/apache/airflow/commit/c67f4af667948e654585e6df102663670804819e>`_  2023-01-09   ``Fix BigQueryColumnCheckOperator runtime error (#28796)``
=================================================================================================  ===========  =========================================================================================================================================================

8.7.0
.....

Latest change: 2023-01-02

=================================================================================================  ===========  =============================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =============================================================================================
`5246c009c5 <https://github.com/apache/airflow/commit/5246c009c557b4f6bdf1cd62bf9b89a2da63f630>`_  2023-01-02   ``Prepare docs for Jan 2023 wave of Providers (#28651)``
`fec1460eb7 <https://github.com/apache/airflow/commit/fec1460eb7896da6bfad69e95c92b8e531e35485>`_  2023-01-01   ``Push job_id in xcom for dataproc submit job op (#28639)``
`0fae6a0c9e <https://github.com/apache/airflow/commit/0fae6a0c9e6e303f4b897a79829f119b44550e01>`_  2022-12-28   ``Add table_resource to template fields for BigQueryCreateEmptyTableOperator (#28235)``
`d7f5f6d737 <https://github.com/apache/airflow/commit/d7f5f6d737cf06cc8e216f523534aeaf48065793>`_  2022-12-24   ``GCSToBigQueryOperator allows autodetect None and infers schema (#28564)``
`034039beb2 <https://github.com/apache/airflow/commit/034039beb2568850d29b34390d3dc1e2a91b8367>`_  2022-12-24   ``Remove 'pylint' messages control instructions (#28555)``
`8fb7be2fb5 <https://github.com/apache/airflow/commit/8fb7be2fb5c64cc2f31a05034087923328b1137a>`_  2022-12-22   ``Set bigquery ''use_legacy_sql'' param in job config correctly (#28522)``
`23264fb820 <https://github.com/apache/airflow/commit/23264fb820c179e9951ea9706f68b13a9b3fdbc0>`_  2022-12-21   ``Fix for issue with reading schema fields for JSON files in GCSToBigQueryOperator (#28284)``
`7950fb9711 <https://github.com/apache/airflow/commit/7950fb9711384f8ac4609fc19f319edb17e296ef>`_  2022-12-21   ``Remove deprecated AIPlatformConsoleLinkk from google/provider.yaml (#28449)``
`820f5a9374 <https://github.com/apache/airflow/commit/820f5a9374b4cc0c5fd2f82b644d55683c42d3a8>`_  2022-12-20   ``Use object instead of array in config.yml for config template (#28417)``
`9eacf607be <https://github.com/apache/airflow/commit/9eacf607be109eb6ab80f7e27d234a17fb128ae0>`_  2022-12-20   ``Fix GCSToBigQueryOperator not respecting schema_obj (#28444)``
`bdf3175e96 <https://github.com/apache/airflow/commit/bdf3175e9616bad3d8b4d8c9f9bbce5530b2cffb>`_  2022-12-06   ``Improve memory usage in Dataproc deferrable operators (#28117)``
`3fef462838 <https://github.com/apache/airflow/commit/3fef46283857114aab46e72d4799c335e9e79f05>`_  2022-12-06   ``Fix GCSToGCSOperator copying list of objects without wildcard (#28111)``
`2d663df055 <https://github.com/apache/airflow/commit/2d663df0552542efcef6e59bc2bc1586f8d1c7f3>`_  2022-12-04   ``Fix: re-enable use of parameters in gcs_to_bq which had been disabled (#27961)``
`5cdff50557 <https://github.com/apache/airflow/commit/5cdff505574822ad3d2a226056246500e4adea2f>`_  2022-12-04   ``Add retry param in GCSObjectExistenceSensor (#27943)``
`8f98bfeb53 <https://github.com/apache/airflow/commit/8f98bfeb5372c7f61c77f081afb9b277c35b88ed>`_  2022-12-03   ``Add preserveAsciiControlCharacters to src_fmt_configs (#27679)``
`4a3a429658 <https://github.com/apache/airflow/commit/4a3a42965801823c39baaccfa96c5e4cffae4012>`_  2022-12-03   ``[misc] Get rid of 'pass' statement in conditions (#27775)``
`6b3bb3c3e9 <https://github.com/apache/airflow/commit/6b3bb3c3e9f8a8d3ff33e5c2b09b0491a4bb6481>`_  2022-12-03   ``Change log level to DEBUG when secret not found for google secret manager (#27856)``
`527b948856 <https://github.com/apache/airflow/commit/527b948856584320f74d385f58477af79506834d>`_  2022-12-03   ``[misc] Replace XOR '^' conditions by 'exactly_one' helper in providers (#27858)``
`c931d88893 <https://github.com/apache/airflow/commit/c931d888936a958ae40b69077d35215227bf1dff>`_  2022-12-03   ``Add deferrable mode to CloudBuildCreateBuildOperator (#27783)``
=================================================================================================  ===========  =============================================================================================

8.6.0
.....

Latest change: 2022-11-26

=================================================================================================  ===========  ==================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==================================================================================
`25bdbc8e67 <https://github.com/apache/airflow/commit/25bdbc8e6768712bad6043618242eec9c6632618>`_  2022-11-26   ``Updated docs for RC3 wave of providers (#27937)``
`f0820e8d9e <https://github.com/apache/airflow/commit/f0820e8d9e8a36325987278bcda2bd69bd53f3a5>`_  2022-11-25   ``Add Export Format to Template Fields in BigQueryToGCSOperator (#27910)``
`2e20e9f7eb <https://github.com/apache/airflow/commit/2e20e9f7ebf5f43bf27069f4c0063cdd72e6b2e2>`_  2022-11-24   ``Prepare for follow-up relase for November providers (#27774)``
`80c327bd3b <https://github.com/apache/airflow/commit/80c327bd3b45807ff2e38d532325bccd6fe0ede0>`_  2022-11-24   ``Bump common.sql provider to 1.3.1 (#27888)``
`bc0063af99 <https://github.com/apache/airflow/commit/bc0063af99629e6b3eb5c76c88ac5bfaf92afaaf>`_  2022-11-16   ``Fix to read location parameter properly in BigQueryToBigQueryOperator (#27661)``
`0cb6450d6d <https://github.com/apache/airflow/commit/0cb6450d6df853e1061dbcafbc437c07a8e0e555>`_  2022-11-16   ``Persist DataprocLink for workflow operators regardless of job status (#26986)``
`ddbc758540 <https://github.com/apache/airflow/commit/ddbc75854019cf6b1e6e5e866eff2796c4f36eff>`_  2022-11-16   ``Deferrable mode for BigQueryToGCSOperator (#27683)``
=================================================================================================  ===========  ==================================================================================

8.5.0
.....

Latest change: 2022-11-15

=================================================================================================  ===========  ==========================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==========================================================================================================
`12c3c39d1a <https://github.com/apache/airflow/commit/12c3c39d1a816c99c626fe4c650e88cf7b1cc1bc>`_  2022-11-15   ``pRepare docs for November 2022 wave of Providers (#27613)``
`00af5c007e <https://github.com/apache/airflow/commit/00af5c007ef2200401b53c40236e664758e47f27>`_  2022-11-14   ``Replace urlparse with urlsplit (#27389)``
`1059de6294 <https://github.com/apache/airflow/commit/1059de6294cf89a085c02036d117000bd98435dc>`_  2022-11-11   ``Dataform operators, links, update system tests and docs (#27144)``
`3aed495f50 <https://github.com/apache/airflow/commit/3aed495f50e8bc0e22ff90efee7671a73168b19e>`_  2022-11-11   ``Rename  hook bigquery function '_bq_cast' to 'bq_cast' (#27543)``
`e8ab8ccc0e <https://github.com/apache/airflow/commit/e8ab8ccc0e7b82efc0dbf8bd31e0bbf57b1d5637>`_  2022-11-11   ``Add backward compatibility with old versions of Apache Beam (#27263)``
`59e3198f7e <https://github.com/apache/airflow/commit/59e3198f7e5f3f4d6999d930fa505e6bd307f325>`_  2022-11-10   ``Change dataprep system tests assets (#26488)``
`98a9c574e3 <https://github.com/apache/airflow/commit/98a9c574e3e30b3aea710c23e18955e88871c9e6>`_  2022-11-08   ``set project_id and location when canceling BigQuery job (#27521)``
`a691ab56a6 <https://github.com/apache/airflow/commit/a691ab56a6544dfab8b3facbceeeee0993beb7c0>`_  2022-11-08   ``Add new Compute Engine Operators and fix system tests (#25608)``
`199359bb38 <https://github.com/apache/airflow/commit/199359bb3886699904ca075de7bd5fdfe5105c5f>`_  2022-11-07   ``Use non-deprecated method for on_kill in BigQueryHook (#27547)``
`7297892558 <https://github.com/apache/airflow/commit/7297892558e94c8cc869b175e904ca96e0752afe>`_  2022-11-07   ``Remove unnecessary newlines around single arg in signature (#27525)``
`5cd78cf425 <https://github.com/apache/airflow/commit/5cd78cf425f6fedc380662ec9a9e37be51403ccb>`_  2022-11-06   ``Upgrade dependencies in order to avoid backtracking (#27531)``
`332c01d6e0 <https://github.com/apache/airflow/commit/332c01d6e0bef41740e8fbc2c9600e7b3066615b>`_  2022-10-31   ``Allow values in WorkflowsCreateExecutionOperator execution argument to be dicts (#27361)``
`50d217a129 <https://github.com/apache/airflow/commit/50d217a1290f891be5d6be743b00b552fc10da20>`_  2022-10-31   ``DataflowStopJobOperator Operator (#27033)``
`eb8c0cf0d2 <https://github.com/apache/airflow/commit/eb8c0cf0d2c657824f666e874ec4e21940931ea4>`_  2022-10-31   ``Migration of System Tests: Cloud Composer (AIP-47)  (#27227)``
`528ecbbc00 <https://github.com/apache/airflow/commit/528ecbbc005566e13f7a6a1cafb4962733c6efb0>`_  2022-10-31   ``Rewrite system tests for ML Engine service (#26915)``
`bcb026bf7c <https://github.com/apache/airflow/commit/bcb026bf7c8031ff64c8b6019d248b12d6aa71e0>`_  2022-10-31   ``use the proper key to retrieve the dataflow job_id (#27336)``
`42841f70d5 <https://github.com/apache/airflow/commit/42841f70d5d385bb19d28a48db93b004b3b34098>`_  2022-10-31   ``Migration of System Tests: Cloud BigQuery Data Transfer (AIP-47) (#27312)``
`1447158e69 <https://github.com/apache/airflow/commit/1447158e690f3d63981b3d8ec065665ec91ca54e>`_  2022-10-31   ``Typecast biquery job response col value (#27236)``
`95e5675714 <https://github.com/apache/airflow/commit/95e5675714f12c177e30d83a14d28222b06d217b>`_  2022-10-31   ``Migration of System Tests: Dataplex (AIP-47) (#26989)``
`124fb3948d <https://github.com/apache/airflow/commit/124fb3948d18c4fe4b2aad12eecfd5ba1efca4bc>`_  2022-10-31   ``Add deferrable mode to GCPToBigQueryOperator + tests (#27052)``
`7a7c5f8fc4 <https://github.com/apache/airflow/commit/7a7c5f8fc4284adfedcb0667ec7c935b913660cf>`_  2022-10-31   ``Add system tests for Vertex AI operators in new approach (#27053)``
`4e55d7fa2b <https://github.com/apache/airflow/commit/4e55d7fa2b7d5f8d63465d2c5270edf2d85f08c6>`_  2022-10-31   ``Migration of System Tests: Cloud Vision Operators (AIP-47) (#26963)``
`896479d1a0 <https://github.com/apache/airflow/commit/896479d1a0624f10a5a9c462071b9c61502cda87>`_  2022-10-31   ``Google Drive to local - system tests migrations (AIP-47) (#26798)``
`3d5f34cb0f <https://github.com/apache/airflow/commit/3d5f34cb0f294d21dd1ba244af0fa06873377f11>`_  2022-10-28   ``Allow and prefer non-prefixed extra fields for dataprep hook (#27039)``
`04f674c13b <https://github.com/apache/airflow/commit/04f674c13bca9af78b65a643240da53aa556e2e1>`_  2022-10-27   ``Migrate Bigtable operators system tests according to AIP-47 (#26911)``
`58d61826a3 <https://github.com/apache/airflow/commit/58d61826a3f47a071c1f0ed4d5b8a5bd01131acb>`_  2022-10-27   ``Migrate Dataproc Metastore system tests according to AIP-47 (#26858)``
`9ab1a6a3e7 <https://github.com/apache/airflow/commit/9ab1a6a3e70b32a3cddddf0adede5d2f3f7e29ea>`_  2022-10-27   ``Update old style typing (#26872)``
`87eb46bbc6 <https://github.com/apache/airflow/commit/87eb46bbc69c20148773d72e990fbd5d20076342>`_  2022-10-26   ``Common sql bugfixes and improvements (#26761)``
`7653c61df8 <https://github.com/apache/airflow/commit/7653c61df894e6c845dde558f5b27f7995415428>`_  2022-10-26   ``Make GSheetsHook return an empty list when there are no values (#27261)``
`78b8ea2f22 <https://github.com/apache/airflow/commit/78b8ea2f22239db3ef9976301234a66e50b47a94>`_  2022-10-24   ``Move min airflow version to 2.3.0 for all providers (#27196)``
`2a34dc9e84 <https://github.com/apache/airflow/commit/2a34dc9e8470285b0ed2db71109ef4265e29688b>`_  2022-10-23   ``Enable string normalization in python formatting - providers (#27205)``
`58378cfd42 <https://github.com/apache/airflow/commit/58378cfd42b137a31032404783b2957284a1e538>`_  2022-10-23   ``Cloud ML Engine operators assets (AIP-47) (#26836)``
`de9633f93a <https://github.com/apache/airflow/commit/de9633f93a366ebc0a46d1ec4df2c4aa9a18357d>`_  2022-10-22   ``Update google hooks to prefer non-prefixed extra fields (#27023)``
`b54a2de8c7 <https://github.com/apache/airflow/commit/b54a2de8c74feb1ea215a98ffaddc5c46713c5cb>`_  2022-10-09   ``Local filesystem to Google Drive Operator - system tests migration (AIP-47) (#26797)``
`b4cef6da21 <https://github.com/apache/airflow/commit/b4cef6da219815b0d5517b4c82fa79bf5274d67a>`_  2022-10-09   ``SFTP to Google Cloud Storage Transfer system tests migration (AIP-47) (#26799)``
`6f0b600293 <https://github.com/apache/airflow/commit/6f0b600293ad53c1c4e3036b0572ca29b98b2fb2>`_  2022-10-09   ``Fix delay in Dataproc CreateBatch operator (#26126)``
`2f326a6c03 <https://github.com/apache/airflow/commit/2f326a6c03efed8788fe0263df96b68abb801088>`_  2022-10-06   ``Remove <2 limit on google-cloud-storage (#26922)``
`a67bcf3eca <https://github.com/apache/airflow/commit/a67bcf3ecaabdff80c551cff1f987523211e7af4>`_  2022-10-06   ``Allow for the overriding of stringify_dict for json/jsonb column data type in Postgres #26875 (#26876)``
=================================================================================================  ===========  ==========================================================================================================

8.4.0
.....

Latest change: 2022-10-04

=================================================================================================  ===========  ========================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ========================================================================================================
`403ed7163f <https://github.com/apache/airflow/commit/403ed7163f3431deb7fc21108e1743385e139907>`_  2022-10-04   ``Add docs for Google/Slack RC providers (#26860)``
`fa0cb363b8 <https://github.com/apache/airflow/commit/fa0cb363b860b553af2ef9530ea2de706bd16e5d>`_  2022-10-01   ``Correcting the transfer config name. (#25719)``
`cee610ae5c <https://github.com/apache/airflow/commit/cee610ae5cf14c117527cdfc9ac2ef0ddb5dcf3b>`_  2022-10-01   ``Fix parsing of optional 'mode' field in BigQuery Result Schema (#26786)``
`b7203cd36e <https://github.com/apache/airflow/commit/b7203cd36eef20de583df3e708f49073d689ac84>`_  2022-10-01   ``Fix MaxID logic for GCSToBigQueryOperator (#26768)``
`f8db64c35c <https://github.com/apache/airflow/commit/f8db64c35c8589840591021a48901577cff39c07>`_  2022-09-28   ``Update docs for September Provider's release (#26731)``
`dce27557eb <https://github.com/apache/airflow/commit/dce27557eb57a4f5748617ba584f9204ac09b10b>`_  2022-09-28   ``Fix GCS sensor system tests failing with DebugExecutor (#26742)``
`26f94c5370 <https://github.com/apache/airflow/commit/26f94c5370587f73ebd935cecf208c6a36bdf9b6>`_  2022-09-26   ``Cloud Data Loss Prevention Operators assets (#26618)``
`01ac40af75 <https://github.com/apache/airflow/commit/01ac40af759c920f4b2d159bcf18001fdaa24ea4>`_  2022-09-22   ``Update gcs.py (#26570)``
`e61d823f18 <https://github.com/apache/airflow/commit/e61d823f18238a82570203b62fe986bd0bc91b51>`_  2022-09-21   ``Cloud Storage Transfer Operators assets & system tests migration (AIP-47) (#26072)``
`a60e3b9317 <https://github.com/apache/airflow/commit/a60e3b9317b2a86e0de44497bfe52fe3b2375c3e>`_  2022-09-21   ``Migrate Data Loss Prevention system tests according to AIP-47 (#26060)``
`c4256ca1a0 <https://github.com/apache/airflow/commit/c4256ca1a029240299b83841bdd034385665cdda>`_  2022-09-21   ``Add BigQuery Column and Table Check Operators (#26368)``
`4c33f6bcf5 <https://github.com/apache/airflow/commit/4c33f6bcf527448283a738ef11478b75ba339422>`_  2022-09-20   ``Merge deferrable BigQuery operators to exisitng one (#26433)``
`8e98b1c6df <https://github.com/apache/airflow/commit/8e98b1c6df067f41226b7f5e4c091955deb83490>`_  2022-09-20   ``Google Drive to Google Cloud Storage Transfer Operator - system tests migration (AIP-47) (#26487)``
`e315900396 <https://github.com/apache/airflow/commit/e31590039634ff722ad005fe9f1fc02e5a669699>`_  2022-09-20   ``specifying project id when calling wait_for_operation in delete/create cluster (#26418)``
`6045f7ad69 <https://github.com/apache/airflow/commit/6045f7ad697e2bdb934add1a8aeae5a817306b22>`_  2022-09-19   ``Cloud Functions Operators assets & system tests migration (AIP-47) (#26073)``
`1f7b296227 <https://github.com/apache/airflow/commit/1f7b296227fee772de9ba15af6ce107937ef9b9b>`_  2022-09-18   ``Auto tail file logs in Web UI (#26169)``
`07fe356de0 <https://github.com/apache/airflow/commit/07fe356de0743ca64d936738b78704f7c05774d1>`_  2022-09-18   ``GCSToBigQueryOperator Resolve 'max_id_key' job retrieval and xcom return (#26285)``
`b4f8a069f0 <https://github.com/apache/airflow/commit/b4f8a069f07b18ce98c9b1286da5a5fcde2bff9f>`_  2022-09-18   ``Allow for the overriding of 'stringify_dict' for json export format on BaseSQLToGCSOperator (#26277)``
`706a618014 <https://github.com/apache/airflow/commit/706a618014a6f94d5ead0476f26f79d9714bf93d>`_  2022-09-18   ``Append GoogleLink base in the link class (#26057)``
`97b144fbed <https://github.com/apache/airflow/commit/97b144fbede1cfecda9e2519eef8183af444e738>`_  2022-09-18   ``Fix JSONDecodeError in Datafusion operators (#26202)``
`9444d9789b <https://github.com/apache/airflow/commit/9444d9789bc88e1063d81d28e219446b2251c0e1>`_  2022-09-14   ``Work around pyupgrade edge cases (#26384)``
`d67ac5932d <https://github.com/apache/airflow/commit/d67ac5932dabbf06ae733fc57b48491a8029b8c2>`_  2022-09-14   ``Apply PEP-563 (Postponed Evaluation of Annotations) to core airflow (#26290)``
`06acf40a43 <https://github.com/apache/airflow/commit/06acf40a4337759797f666d5bb27a5a393b74fed>`_  2022-09-13   ``Apply PEP-563 (Postponed Evaluation of Annotations) to non-core airflow (#26289)``
`23ad7e292a <https://github.com/apache/airflow/commit/23ad7e292a29e43436170078ae132569f8fbf1e4>`_  2022-09-10   ``Cloud Video Intelligence Operators assets & system tests migration (AIP-47) (#26132)``
`3a539ff663 <https://github.com/apache/airflow/commit/3a539ff6631109dc58514339ac60672f031c7054>`_  2022-09-09   ``Life Science assets & system tests migration (AIP-47) (#25548)``
`5066844513 <https://github.com/apache/airflow/commit/50668445137e4037bb4a3b652bec22e53d1eddd7>`_  2022-09-09   ``D400 first line should end with period batch02 (#25268)``
`f938cd4fc8 <https://github.com/apache/airflow/commit/f938cd4fc867513e729aa9a005d663c9713f74e6>`_  2022-09-08   ``Add deferrable big query operators and sensors (#26156)``
`8cac96918b <https://github.com/apache/airflow/commit/8cac96918becf19a4a04eef1e5bcf175f815f204>`_  2022-09-07   ``GCSToBigQueryOperator allow for schema_object in alternate GCS Bucket (#26190)``
`12cbc0f1dd <https://github.com/apache/airflow/commit/12cbc0f1ddd9e8a66c5debe7f97b55a2c8001502>`_  2022-09-07   ``Don't throw an exception when a BQ cusor job has no schema (#26096)``
`8acdc2a834 <https://github.com/apache/airflow/commit/8acdc2a834b9c4e287fe612ed56ab8908d777609>`_  2022-08-30   ``Replace SQL with Common SQL in pre commit (#26058)``
`1d06374194 <https://github.com/apache/airflow/commit/1d06374194586d6dd857e95c866925e9034d9a48>`_  2022-08-30   ``Hook into Mypy to get rid of those cast() (#26023)``
`da8f133053 <https://github.com/apache/airflow/commit/da8f133053f7483cfe45109142943a7ded1ed1a2>`_  2022-08-29   ``Use AsyncClient for Composer Operators in deferrable mode (#25951)``
`1ed014647e <https://github.com/apache/airflow/commit/1ed014647e7293d342d9d1c2706343a68f003655>`_  2022-08-29   ``Add 'output' property to MappedOperator (#25604)``
`d4eb60712d <https://github.com/apache/airflow/commit/d4eb60712dc7bb34960ae10b9e6dd8624a554dfc>`_  2022-08-27   ``Use project_id to get authenticated client (#25984)``
`4c3fb1ff2b <https://github.com/apache/airflow/commit/4c3fb1ff2b789320cc2f19bd921ac0335fc8fdf1>`_  2022-08-27   ``Google Cloud Tasks Sensor for queue being empty (#25622)``
`c81178063a <https://github.com/apache/airflow/commit/c81178063aad41925be4de4eb3ee89e3d3e31fa0>`_  2022-08-27   ``Cloud Build assets & system tests migration (AIP-47) (#25895)``
`62a46c1e18 <https://github.com/apache/airflow/commit/62a46c1e1812422966b5af33cd4b42e24fe0edc5>`_  2022-08-27   ``Added append_job_name parameter to DataflowTemplatedJobStartOperator (#25746)``
`15b49add28 <https://github.com/apache/airflow/commit/15b49add282e88b02711a2d3afec614fd31f12c5>`_  2022-08-23   ``Sql to GSC operators update docs for parquet format (#25878)``
`25a9ae3b2e <https://github.com/apache/airflow/commit/25a9ae3b2eec85dfd500b0a921045fc95ab8ffd6>`_  2022-08-23   ``Limit Google Protobuf for compatibility with biggtable client (#25886)``
`ecf0460b7d <https://github.com/apache/airflow/commit/ecf0460b7d9c9e9b6462c3dfa92cdf4e373dbfd5>`_  2022-08-22   ``Dataproc submit job operator async (#25302)``
`fc6dfa338a <https://github.com/apache/airflow/commit/fc6dfa338a76d02a426e2b7f0325d37ea5e95ac3>`_  2022-08-20   ``Support project_id argument in BigQueryGetDataOperator (#25782)``
`6e66dd7776 <https://github.com/apache/airflow/commit/6e66dd7776707936345927f8fccee3ddb7f23a2b>`_  2022-08-19   ``Make GoogleBaseHook credentials functions public (#25785)``
`6e41c7eb33 <https://github.com/apache/airflow/commit/6e41c7eb33a68ea3ccd6b67fb169ea2cf1ecc162>`_  2022-08-16   ``Fixed never ending loop to in CreateWorkflowInvocation (#25737)``
`6c5b0776c0 <https://github.com/apache/airflow/commit/6c5b0776c07c6317e6e2eea67964a07cdadf2394>`_  2022-08-14   ``Adding a parameter for exclusion of trashed files in GoogleDriveHook (#25675)``
`1b412c9cbe <https://github.com/apache/airflow/commit/1b412c9cbe48235cf02bb57a94c0d47d3f86df20>`_  2022-08-10   ``Consolidate to one 'schedule' param (#25410)``
=================================================================================================  ===========  ========================================================================================================

8.3.0
.....

Latest change: 2022-08-10

=================================================================================================  ===========  ==================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==================================================================================
`e5ac6c7cfb <https://github.com/apache/airflow/commit/e5ac6c7cfb189c33e3b247f7d5aec59fe5e89a00>`_  2022-08-10   ``Prepare docs for new providers release (August 2022) (#25618)``
`2e2d4bffd5 <https://github.com/apache/airflow/commit/2e2d4bffd53a94fda04e7d88843545f7070b6f32>`_  2022-08-09   ``Dataform operators (#25587)``
`c8c4a42723 <https://github.com/apache/airflow/commit/c8c4a4272354d090ebf01a5cf7a9f49026e65511>`_  2022-08-08   ``Fix GCSListObjectsOperator docstring (#25614)``
`029e3ae96f <https://github.com/apache/airflow/commit/029e3ae96f50074e9b524f0b820573741432f44a>`_  2022-08-05   ``Remove deprecated modules (#25543)``
`7d2c2ee879 <https://github.com/apache/airflow/commit/7d2c2ee879656faf47829d1ad89fc4441e19a66e>`_  2022-08-04   ``add description method in BigQueryCursor class (#25366)``
`e84d753015 <https://github.com/apache/airflow/commit/e84d753015e5606c29537741cdbe8ae08012c3b6>`_  2022-08-04   ``Fix BigQueryInsertJobOperator cancel_on_kill (#25342)``
`803c0e252f <https://github.com/apache/airflow/commit/803c0e252fc78a424a181a34a93e689fa9aaaa09>`_  2022-08-03   ``Fix BaseSQLToGCSOperator approx_max_file_size_bytes (#25469)``
`faf3c4fe47 <https://github.com/apache/airflow/commit/faf3c4fe474733965ab301465f695e3cc311169c>`_  2022-08-02   ``Fix PostgresToGCSOperat bool dtype (#25475)``
`c8cacad4d6 <https://github.com/apache/airflow/commit/c8cacad4d63361b52b5790b4a75c8f928f1eca83>`_  2022-08-02   ``Migrate Google example trino_to_gcs to new design AIP-47 (#25420)``
`d2900022a2 <https://github.com/apache/airflow/commit/d2900022a27373b09a3a2a68f8bbc26fbba4a64e>`_  2022-08-02   ``Migrate Google example automl_nl_text_extraction to new design AIP-47 (#25418)``
`acab8f52dd <https://github.com/apache/airflow/commit/acab8f52dd8d90fd6583779127895dd343780f79>`_  2022-07-29   ``Move all "old" SQL operators to common.sql providers (#25350)``
`f6b48ac6df <https://github.com/apache/airflow/commit/f6b48ac6dfaf931a5433ec16369302f68f038c65>`_  2022-07-28   ``Memorystore assets & system tests migration (AIP-47) (#25361)``
`f4b93cc097 <https://github.com/apache/airflow/commit/f4b93cc097dab95437c9c4b37474f792f80fd14e>`_  2022-07-28   ``Translate system tests migration (AIP-47) (#25340)``
`a8e4519815 <https://github.com/apache/airflow/commit/a8e451981572fa09a96660992e68e046c4baa75f>`_  2022-07-28   ``Fix Vertex AI Custom Job training issue (#25367)``
`5d4abbd58c <https://github.com/apache/airflow/commit/5d4abbd58c33e7dfa8505e307d43420459d3df55>`_  2022-07-27   ``Deprecate hql parameters and synchronize DBApiHook method APIs (#25299)``
`8bc147192c <https://github.com/apache/airflow/commit/8bc147192c8e7174f9e0c9b55b2f5461f7227bcf>`_  2022-07-27   ``Fix Flask Login user setting for Flask 2.2 and Flask-Login 0.6.2 (#25318)``
`28db8c10b2 <https://github.com/apache/airflow/commit/28db8c10b2422d99217658a039cc6dc45a38ff51>`_  2022-07-26   ``Migrate Google example life_sciences to new design AIP-47 (#25264)``
`10c9a3697a <https://github.com/apache/airflow/commit/10c9a3697a52ba54996df42740d1e929b3a78d43>`_  2022-07-26   ``Migrate Google example natural_language to new design AIP-47 (#25262)``
`b288bf4da4 <https://github.com/apache/airflow/commit/b288bf4da44301d91ae62131976eb2925decd0aa>`_  2022-07-26   ``Delete redundant system test bigquery_to_bigquery (#25261)``
`c8af0592c0 <https://github.com/apache/airflow/commit/c8af0592c08017ee48f69f608ad4a6529ee14292>`_  2022-07-26   ``Improve taskflow type hints with ParamSpec (#25173)``
`df00436569 <https://github.com/apache/airflow/commit/df00436569bb6fb79ce8c0b7ca71dddf02b854ef>`_  2022-07-22   ``Unify DbApiHook.run() method with the methods which override it (#23971)``
`66b3ca1d28 <https://github.com/apache/airflow/commit/66b3ca1d2837610e01cf1d2314fadcc4be0a111c>`_  2022-07-21   ``Migrate Google example bigquery_to_mssql to new design AIP-47 (#25174)``
`9644451676 <https://github.com/apache/airflow/commit/96444516761a3be34616b773d5108795ea514fdb>`_  2022-07-19   ``Migrate Google example compute_igm to new design AIP-47 (#25132)``
`3a80b36ed9 <https://github.com/apache/airflow/commit/3a80b36ed98be62dd42ede0f4afab0f16a8306be>`_  2022-07-19   ``Migrate Google example automl_vision to new design AIP-47 (#25152)``
`c0ce8a8375 <https://github.com/apache/airflow/commit/c0ce8a83757043110025b57d7fdc3825454d54d2>`_  2022-07-18   ``Migrate Google example gcs_to_sftp to new design AIP-47 (#25107)``
`e32e9c5880 <https://github.com/apache/airflow/commit/e32e9c58802fe9363cc87ea283a59218df7cec3a>`_  2022-07-18   ``Bump typing-extensions and mypy for ParamSpec (#25088)``
`4473b27d08 <https://github.com/apache/airflow/commit/4473b27d089ff28d3d73af7c4a8bc6e011134b50>`_  2022-07-16   ``Migrate Google campaign manager example to new design AIP-47 (#25069)``
`9b7e4a7324 <https://github.com/apache/airflow/commit/9b7e4a732496e60ef1c275c1ac17c7ed05b27b54>`_  2022-07-16   ``Migrate Google analytics example to new design AIP-47 (#25006)``
`77626b7fc8 <https://github.com/apache/airflow/commit/77626b7fc8ad57e71b3e93f81429424bdfa002a3>`_  2022-07-13   ``Add project_id as a templated variable in two BQ operators (#24768)``
=================================================================================================  ===========  ==================================================================================

8.2.0
.....

Latest change: 2022-07-13

=================================================================================================  ===========  ====================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ====================================================================================
`d2459a241b <https://github.com/apache/airflow/commit/d2459a241b54d596ebdb9d81637400279fff4f2d>`_  2022-07-13   ``Add documentation for July 2022 Provider's release (#25030)``
`93992f2361 <https://github.com/apache/airflow/commit/93992f2361a24bad61fc71a6078fa553cd66b302>`_  2022-07-12   ``PubSub assets & system tests migration (AIP-47) (#24867)``
`a13c51e224 <https://github.com/apache/airflow/commit/a13c51e224e6299387d8b704e12cb7b4c8f61718>`_  2022-07-12   ``Migrate Google sheets example to new design AIP-47 (#24975)``
`a038b52b5a <https://github.com/apache/airflow/commit/a038b52b5a3bd4a0c97edf9f95da25b2316d305e>`_  2022-07-12   ``Migrate Google ads example to new design AIP-47 (#24941)``
`c618da444e <https://github.com/apache/airflow/commit/c618da444e841afcfd73eeb0bce9c87648c89140>`_  2022-07-12   ``Modify BigQueryCreateExternalTableOperator to use updated hook function (#24363)``
`626d9db290 <https://github.com/apache/airflow/commit/626d9db2908563c4b7675db5de2cb1e3acde82e9>`_  2022-07-12   ``Migrate Google example gcs_to_gdrive to new design AIP-47 (#24949)``
`fb51e04cfd <https://github.com/apache/airflow/commit/fb51e04cfdbe1a5f80eb51d9ffc3db4bb57a7c34>`_  2022-07-12   ``Migrate Google firestore example to new design AIP-47 (#24830)``
`b777514253 <https://github.com/apache/airflow/commit/b7775142530d053527b0f21f48e04b95ca8861ab>`_  2022-07-12   ``Add handling state of existing Dataproc batch (#24924)``
`acaa0635c8 <https://github.com/apache/airflow/commit/acaa0635c8477c98ab78da9f6d86e6f1bad2737d>`_  2022-07-08   ``Automatically detect if non-lazy logging interpolation is used (#24910)``
`fb7162418e <https://github.com/apache/airflow/commit/fb7162418eeacac626467871a7ed5567f20840ac>`_  2022-07-07   ``Add links for Google Kubernetes Engine operators (#24786)``
`46bbfdade0 <https://github.com/apache/airflow/commit/46bbfdade0638cb8a5d187e47034b84e68ddf762>`_  2022-07-07   ``Move all SQL classes to common-sql provider (#24836)``
`80b6754746 <https://github.com/apache/airflow/commit/80b6754746dc0dbb680c181f6292225f4d4a080d>`_  2022-07-06   ``Migrate Google example sql_to_sheets to new design AIP-47 (#24814)``
`3b35325840 <https://github.com/apache/airflow/commit/3b35325840e484f86df00e087410f5d5da4b9130>`_  2022-07-06   ``Add test_connection method to 'GoogleBaseHook' (#24682)``
`96b01a8012 <https://github.com/apache/airflow/commit/96b01a8012d164df7c24c460149d3b79ecad3901>`_  2022-07-05   ``Remove "bad characters" from our codebase (#24841)``
`9227d56e68 <https://github.com/apache/airflow/commit/9227d56e681a40e9caf2eefae87f7046c0d0c9f4>`_  2022-07-04   ``Datacatalog assets & system tests migration (AIP-47) (#24600)``
`fe13eae3bf <https://github.com/apache/airflow/commit/fe13eae3bf0542025e622e51a487f8d6a8b6d2c5>`_  2022-07-04   ``perf(BigQuery): pass table_id as str type (#23141)``
`37ea530cb7 <https://github.com/apache/airflow/commit/37ea530cb786c994d5d02c9719ca4ae3ed8b44b2>`_  2022-07-04   ``Migrate Google example DAG mssql_to_gcs to new design AIP-47 (#24541)``
`46ac083f7e <https://github.com/apache/airflow/commit/46ac083f7e92cf8af046c8b5741e7c26ebffc05e>`_  2022-07-01   ``Align Black and blacken-docs configs (#24785)``
`0de31bd73a <https://github.com/apache/airflow/commit/0de31bd73a8f41dded2907f0dee59dfa6c1ed7a1>`_  2022-06-29   ``Move provider dependencies to inside provider folders (#24672)``
`45b11d4ed1 <https://github.com/apache/airflow/commit/45b11d4ed1412c00ebf32a03ab5ea3a06274f208>`_  2022-06-29   ``Use our yaml util in all providers (#24720)``
`510a6bab45 <https://github.com/apache/airflow/commit/510a6bab4595cce8bd5b1447db957309d70f35d9>`_  2022-06-28   ``Remove 'hook-class-names' from provider.yaml (#24702)``
`7a7ca50160 <https://github.com/apache/airflow/commit/7a7ca5016019f93ebee052a2bf99772145b7fc03>`_  2022-06-28   ``Migrate Google example DAG s3_to_gcs to new design AIP-47 (#24641)``
`abb304c92f <https://github.com/apache/airflow/commit/abb304c92f63261e55c5dca1a7be9aa5ac18ec85>`_  2022-06-25   ``Migrate Google example DAG bigquery_transfer to new design AIP-47 (#24543)``
`ded22eb5b6 <https://github.com/apache/airflow/commit/ded22eb5b65bbc789c3f1842402e343070b96f19>`_  2022-06-24   ``Add gcp_conn_id argument to GoogleDriveToLocalOperator (#24622)``
`e2f19505bf <https://github.com/apache/airflow/commit/e2f19505bf3622935480e80bee55bf5b6d80097b>`_  2022-06-22   ``Upgrade FAB to 4.1.1 (#24399)``
`9c59831ee7 <https://github.com/apache/airflow/commit/9c59831ee78f14de96421c74986933c494407afa>`_  2022-06-21   ``Update providers to use functools compat for ''cached_property'' (#24582)``
`88ddf65708 <https://github.com/apache/airflow/commit/88ddf65708ce65bc166e7e0d0bd21c3896dc3053>`_  2022-06-20   ``Migrate Google example DAG oracle_to_gcs to new design AIP-47 (#24542)``
`32fc4be502 <https://github.com/apache/airflow/commit/32fc4be502b3d1b60681e38b7b6947445987ec19>`_  2022-06-20   ``Migrate Google example DAG mysql_to_gcs to new design AIP-47 (#24540)``
`a35f342833 <https://github.com/apache/airflow/commit/a35f3428333f9ee793fac9998d76784044e3d85c>`_  2022-06-20   ``Migrate Google search_ads DAG to new design AIP-47 (#24298)``
`e7a1c50d62 <https://github.com/apache/airflow/commit/e7a1c50d62680a521ef90a424b7eff03635081d5>`_  2022-06-20   ``GCSDeleteObjectsOperator empty prefix bug fix (#24353)``
`dd35fdaf35 <https://github.com/apache/airflow/commit/dd35fdaf35b6e46fd69a1b1da36ae7ffc0505dcb>`_  2022-06-20   ``Migrate Google gcs_to_sheets DAG to new design AIP-47 (#24501)``
`0561c1aac4 <https://github.com/apache/airflow/commit/0561c1aac4d0ba6ddebfe086243e2d148a394214>`_  2022-06-19   ``Add DeprecationWarning for column_transformations parameter in AutoML (#24467)``
=================================================================================================  ===========  ====================================================================================

8.1.0
.....

Latest change: 2022-06-15

=================================================================================================  ===========  ============================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ============================================================================================
`952a5ea8d8 <https://github.com/apache/airflow/commit/952a5ea8d87bd1a53228e8645538a2d0c545e0d2>`_  2022-06-15   ``Update release docs for Google and Oracle providers (#24461)``
`ce50d3731a <https://github.com/apache/airflow/commit/ce50d3731a049047d31d09c6d38a470b84cf57e7>`_  2022-06-15   ``Use insert_job in the BigQueryToGCPOpertor and adjust links (#24416)``
`2a084ee8d7 <https://github.com/apache/airflow/commit/2a084ee8d7fb27cbc3ad28f4845c5d20c82f0cbe>`_  2022-06-14   ``Update Oracle library to latest version (#24311)``
`69c46252dd <https://github.com/apache/airflow/commit/69c46252dd222fbcbfdd035ce6de1868b719023f>`_  2022-06-14   ``fix typo in google provider additional extras (#24431)``
`08b675cf66 <https://github.com/apache/airflow/commit/08b675cf6642171cb1c5ddfb09607b541db70b29>`_  2022-06-13   ``Fix links to sources for examples (#24386)``
`94257f48f4 <https://github.com/apache/airflow/commit/94257f48f4a3f123918b0d55c34753c7c413eb74>`_  2022-06-13   ``Expose SQL to GCS Metadata (#24382)``
`8e0bddaea6 <https://github.com/apache/airflow/commit/8e0bddaea69db4d175f03fa99951f6d82acee84d>`_  2022-06-12   ``Deprecate remaining occurrences of 'bigquery_conn_id' in favor of 'gcp_conn_id' (#24376)``
`6eb60f816c <https://github.com/apache/airflow/commit/6eb60f816cb6103d42c023ce5fba9ac31a64f9ce>`_  2022-06-12   ``Migrate Google calendar example DAG to new design AIP-47 (#24333)``
`bc3fc8c9fc <https://github.com/apache/airflow/commit/bc3fc8c9fcb5d1291797aa5f4fc8da954573c694>`_  2022-06-12   ``Migrate Google azure_fileshare example DAG to new design AIP-47 (#24349)``
`6ab02b69a0 <https://github.com/apache/airflow/commit/6ab02b69a0bbc398e9e41c70d78487d3255b0585>`_  2022-06-12   ``Remove bigquery example already migrated to AIP-47 (#24379)``
`cb90ca7afb <https://github.com/apache/airflow/commit/cb90ca7afbbca9911fc2104f331354b6d1a63758>`_  2022-06-12   ``Migrate Google sheets example DAG to new design AIP-47 (#24351)``
=================================================================================================  ===========  ============================================================================================

8.0.0
.....

Latest change: 2022-06-09

=================================================================================================  ===========  =======================================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =======================================================================================================================
`dcdcf3a2b8 <https://github.com/apache/airflow/commit/dcdcf3a2b8054fa727efb4cd79d38d2c9c7e1bd5>`_  2022-06-09   ``Update release notes for RC2 release of Providers for May 2022 (#24307)``
`047a6162b0 <https://github.com/apache/airflow/commit/047a6162b0b4cbf07fe2fd978e335839a7d3900b>`_  2022-06-08   ``Workaround job race bug on biguery to gcs transfer (#24330)``
`717a7588bc <https://github.com/apache/airflow/commit/717a7588bc8170363fea5cb75f17efcf68689619>`_  2022-06-07   ``Update package description to remove double min-airflow specification (#24292)``
`b1ad017cee <https://github.com/apache/airflow/commit/b1ad017cee66f5e042144cc7baa2d44b23b47c4f>`_  2022-06-07   ``pydocstyle D202 added (#24221)``
`aeabe994b3 <https://github.com/apache/airflow/commit/aeabe994b3381d082f75678a159ddbb3cbf6f4d3>`_  2022-06-07   ``Prepare docs for May 2022 provider's release (#24231)``
`c3a9ef1ada <https://github.com/apache/airflow/commit/c3a9ef1adadc1e39536f60db46017870860fc633>`_  2022-06-07   ``AIP-47 - Migrate google leveldb DAGs to new design ##22447 (#24233)``
`c23826915d <https://github.com/apache/airflow/commit/c23826915dcdca4f22b52b74633336cb2f4a1eca>`_  2022-06-07   ``Apply per-run log templates to log handlers (#24153)``
`80c1ce76e1 <https://github.com/apache/airflow/commit/80c1ce76e19d363916f2253cdd536372f6a43aee>`_  2022-06-06   ``Cloud Storage assets & StorageLink update (#23865)``
`ec84ffe71c <https://github.com/apache/airflow/commit/ec84ffe71cfa8246155b9b4cb10bf2167e75adcf>`_  2022-06-06   ``Fix GCSToGCSOperator cannot copy a single file/folder without copying other files/folders with that prefix (#24039)``
`027b707d21 <https://github.com/apache/airflow/commit/027b707d215a9ff1151717439790effd44bab508>`_  2022-06-05   ``Add explanatory note for contributors about updating Changelog (#24229)``
`55fd02a389 <https://github.com/apache/airflow/commit/55fd02a38919526776cfe69d715873da75d6f26f>`_  2022-06-04   ``Add key_secret_project_id parameter which specifies a project with KeyFile (#23930)``
`90233bc7cb <https://github.com/apache/airflow/commit/90233bc7cbb95d7de6e4de3b7b1206eebf5ad28c>`_  2022-06-04   ``Added impersonation_chain for DataflowStartFlexTemplateOperator and DataflowStartSqlJobOperator (#24046)``
`c01a5a50b4 <https://github.com/apache/airflow/commit/c01a5a50b44bf2cd0d980123549e3c8d5cfe7521>`_  2022-06-04   ``Fix BigQuery system tests (#24013)``
`a597a76e8f <https://github.com/apache/airflow/commit/a597a76e8f893865e7380b072de612763639bfb9>`_  2022-06-03   ``fix BigQueryInsertJobOperator (#24165)``
`e13b15946e <https://github.com/apache/airflow/commit/e13b15946ee2db956040f81ca374cb4619d07cf1>`_  2022-06-03   ``Workflows assets & system tests migration (AIP-47) (#24105)``
`368f292ca1 <https://github.com/apache/airflow/commit/368f292ca12f13e1520ad77ab500123e13c82932>`_  2022-06-03   ``Update credentials when using ADC in Compute Engine (#23773)``
`96e8fb4a07 <https://github.com/apache/airflow/commit/96e8fb4a07d559946ad5889d1af2c80607f78cfc>`_  2022-06-01   ``Fix the link to google workplace (#24080)``
`3dd7b1ddba <https://github.com/apache/airflow/commit/3dd7b1ddbaa3170fbda30a8323286abf075f30ba>`_  2022-06-01   ``set color to operators in cloud_sql.py (#24000)``
`841ed27101 <https://github.com/apache/airflow/commit/841ed271017ff35a3124f1d1a53a5c74730fed60>`_  2022-06-01   ``Spanner assets & system tests migration (AIP-47) (#23957)``
`fedab9d64a <https://github.com/apache/airflow/commit/fedab9d64a58f1b5d3c88fe7a67f1f4021db8d26>`_  2022-06-01   ``Remove hack from BigQuery DTS hook (#23887)``
`e58985598f <https://github.com/apache/airflow/commit/e58985598f202395098e15b686aec33645a906ff>`_  2022-05-30   ``Ensure @contextmanager decorates generator func (#23103)``
`92ddcf4ac6 <https://github.com/apache/airflow/commit/92ddcf4ac6fa452c5056b1f7cad1fca4d5759802>`_  2022-05-27   ``Introduce 'flake8-implicit-str-concat' plugin to static checks (#23873)``
`ec6761a5c0 <https://github.com/apache/airflow/commit/ec6761a5c0d031221d53ce213c0e42813606c55d>`_  2022-05-23   ``Clean up f-strings in logging calls (#23597)``
`65f3b18fc1 <https://github.com/apache/airflow/commit/65f3b18fc1142c0d23e715fa1a98f21662df9584>`_  2022-05-22   ``Sql to gcs with exclude columns (#23695)``
`a43e98d050 <https://github.com/apache/airflow/commit/a43e98d05047d9c4d5a7778bcb10efc4bdef7a01>`_  2022-05-22   ``Fix DataprocJobBaseOperator not being compatible with dotted names (#23439). (#23791)``
`5bfacf81c6 <https://github.com/apache/airflow/commit/5bfacf81c63668ea63e7cb48f4a708a67d0ac0a2>`_  2022-05-20   ``[Issue#22846] allow option to encode or not encode UUID when uploading from Cassandra to GCS (#23766)``
`f60fa98a2e <https://github.com/apache/airflow/commit/f60fa98a2ef587f02f93dac95d4db39c825a87b1>`_  2022-05-19   ``Cloud SQL assets & system tests migration (AIP-47) (#23583)``
`d3b0880286 <https://github.com/apache/airflow/commit/d3b08802861b006fc902f895802f460a72d504b0>`_  2022-05-17   ``Speech To Text assets & system tests migration (AIP-47) (#23643)``
`3bf9a1df38 <https://github.com/apache/airflow/commit/3bf9a1df38b1ccfaf965a207d047b30452df1ba5>`_  2022-05-16   ``Add fields to CLOUD_SQL_EXPORT_VALIDATION. (#23724)``
`bc0dcddfb5 <https://github.com/apache/airflow/commit/bc0dcddfb5e286f0be445f6d09f190a1cbcb6093>`_  2022-05-12   ``Migrate Dataproc to new system tests design (#22777)``
=================================================================================================  ===========  =======================================================================================================================

7.0.0
.....

Latest change: 2022-05-12

=================================================================================================  ===========  ===================================================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ===================================================================================================================================
`75c60923e0 <https://github.com/apache/airflow/commit/75c60923e01375ffc5f71c4f2f7968f489e2ca2f>`_  2022-05-12   ``Prepare provider documentation 2022.05.11 (#23631)``
`cd49a8b9f6 <https://github.com/apache/airflow/commit/cd49a8b9f64c57b5622025baee9247712c692e72>`_  2022-05-11   ``[FEATURE] google provider - BigQueryInsertJobOperator log query (#23648)``
`60a1d9d191 <https://github.com/apache/airflow/commit/60a1d9d191fb8fc01893024c897df9632ad5fbf4>`_  2022-05-10   ``[FEATURE] google provider - split GkeStartPodOperator execute (#23518)``
`74557e41e3 <https://github.com/apache/airflow/commit/74557e41e3dcedec241ea583123d53176994cccc>`_  2022-05-10   ``Add exportContext.offload flag to CLOUD_SQL_EXPORT_VALIDATION. (#23614)``
`428a439953 <https://github.com/apache/airflow/commit/428a43995390b3623a51aa7bac7e21da69a8db22>`_  2022-05-09   ``Clean up in-line f-string concatenation (#23591)``
`766726f2e3 <https://github.com/apache/airflow/commit/766726f2e3a282fcd2662f5dc6e9926dc38a6540>`_  2022-05-09   ``Fix 'PostgresToGCSOperator' does not allow nested JSON (#23063)``
`82c244f9c7 <https://github.com/apache/airflow/commit/82c244f9c7f24735ee952951bcb5add45422d186>`_  2022-05-08   ``Fix GCSToGCSOperator ignores replace parameter when there is no wildcard (#23340)``
`627b5698ec <https://github.com/apache/airflow/commit/627b5698ec6b1b62c75a57953bb7ee7a45c56f3c>`_  2022-05-04   ``Add Stackdriver assets and migrate system tests to AIP-47 (#23320)``
`3977e1798d <https://github.com/apache/airflow/commit/3977e1798d8294ba628b5f330f43702c1a5c79fc>`_  2022-05-04   ``CloudTasks assets & system tests migration (AIP-47) (#23282)``
`dfe0f75938 <https://github.com/apache/airflow/commit/dfe0f759381c13a2c81212368d3c0c43f57da660>`_  2022-05-04   ``TextToSpeech assets & system tests migration (AIP-47) (#23247)``
`2d109401b3 <https://github.com/apache/airflow/commit/2d109401b3566aef613501691d18cf7e4c776cd2>`_  2022-05-04   ``Bump pre-commit hook versions (#22887)``
`427e14b763 <https://github.com/apache/airflow/commit/427e14b763d2a29432a999ba6b984fcccc11977a>`_  2022-05-03   ``Fix code-snippets in google provider (#23438)``
`fa0cc7cec7 <https://github.com/apache/airflow/commit/fa0cc7cec7572c948ebd250a6d7f008ddf222433>`_  2022-05-02   ``Cleanup Google provider CHANGELOG.rst (#23390)``
`3f6d5eef42 <https://github.com/apache/airflow/commit/3f6d5eef427f3ea33d0cd342143983f54226bf05>`_  2022-05-01   ``'DataprocHook': Remove deprecated function 'submit' (#23389)``
`511d0ee256 <https://github.com/apache/airflow/commit/511d0ee256b819690ccf0f6b30d12340b1dd7f0a>`_  2022-04-30   ``Bigquery assets (#23165)``
`3f9845095e <https://github.com/apache/airflow/commit/3f9845095e5e51595af73c237491c04012ddbbd9>`_  2022-04-29   ``Remove redundant docstring in 'BigQueryUpdateTableSchemaOperator' (#23349)``
`0fcdc5e1fb <https://github.com/apache/airflow/commit/0fcdc5e1fb4f49bc9c35eec99a6c3ea65f704588>`_  2022-04-29   ``'S3ToGCSOperator': Remove 'dest_gcs_conn_id' (#23348)``
`05ccfd42f2 <https://github.com/apache/airflow/commit/05ccfd42f28db7d0a8fe3ed023b0e7a8ec188609>`_  2022-04-29   ``Dataproc: Remove default value of 'region' (#23350)``
`359dc58207 <https://github.com/apache/airflow/commit/359dc582078e0d128f42a983c285ffec7ad41686>`_  2022-04-29   ``Google provider: Remove 'bigquery_conn_id', 'google_cloud_storage_conn_id' (#23326)``
`c82b3b9466 <https://github.com/apache/airflow/commit/c82b3b94660a38360f61d47676ed180a0d32c189>`_  2022-04-28   ``'GCSFileTransformOperator': New templated fields 'source_object', 'destination_object' (#23328)``
`9449a107f0 <https://github.com/apache/airflow/commit/9449a107f092f2f6cfa9c8bbcf5fd62fadfa01be>`_  2022-04-28   ``'DatastoreHook': Remove 'datastore_conn_id' (#23323)``
`1f32603549 <https://github.com/apache/airflow/commit/1f3260354988b304cf31d5e1d945ce91798bed48>`_  2022-04-28   ``update processor to fix broken download URLs (#23299)``
`8a7b61a8e4 <https://github.com/apache/airflow/commit/8a7b61a8e4e912627af0b84128ad87c0a347b1d8>`_  2022-04-28   ``Migrate gcs to new system tests design (#22778)``
`72e2ea68a1 <https://github.com/apache/airflow/commit/72e2ea68a13f6494d1d95d6e03bc5ed72f4c8342>`_  2022-04-27   ``'CloudBuildCreateBuildOperator': Remove deprecated 'body' parameter (#23263)``
`6cf0176f2a <https://github.com/apache/airflow/commit/6cf0176f2a676008a6fbe5b950ab2e3231fd1f76>`_  2022-04-27   ``Remove deprecated parameters from PubSub operators: (#23261)``
`4d9c55c9d9 <https://github.com/apache/airflow/commit/4d9c55c9d962f179ae4d7c9e7c697b01cea8d0d2>`_  2022-04-27   ``Remove deprecated parameters from BigQueryHook: (#23269)``
`915b0c689e <https://github.com/apache/airflow/commit/915b0c689eb1e40a2e4496991b74379fed2cfe90>`_  2022-04-27   ``add missing docstring in 'BigQueryHook.create_empty_table' (#23270)``
`710eb6f3e6 <https://github.com/apache/airflow/commit/710eb6f3e606c32aa8a518915d2930abeb69f659>`_  2022-04-26   ``* 'CloudDatastoreImportEntitiesOperator' : Remove 'xcom_push'. Please use 'BaseOperator.do_xcom_push' (#23252)``
`2d569fdaf0 <https://github.com/apache/airflow/commit/2d569fdaf0727bfe7f3a92fa4ce9ae47236d3615>`_  2022-04-26   ``Create links for Biqtable operators (#23164)``
`434ab5a03c <https://github.com/apache/airflow/commit/434ab5a03ce2f34570bb4d9b7fb1e22c8e6762e2>`_  2022-04-26   ``'BigtableCreateInstanceOperator' & 'BigtableHook.create_instance' Remove 'replica_cluster_id', 'replica_cluster_zone'. (#23251)``
`5ca1f3bf70 <https://github.com/apache/airflow/commit/5ca1f3bf706f6ac8437bef0c7c4944cc2d7fca04>`_  2022-04-26   ``Dataproc : remove 'location' in favor of 'region' (#23250)``
`1416ac4195 <https://github.com/apache/airflow/commit/1416ac4195654088b10e9af107282f6b0464105c>`_  2022-04-26   ``'PubSubPullSensor': Remove 'project' and 'return_immediately' (#23231)``
`06dfc2536c <https://github.com/apache/airflow/commit/06dfc2536c0bcddec478ff61cdc8677d9bc64435>`_  2022-04-26   ``Remove deprecated 'params' from google operators (#23230)``
`37a7b27242 <https://github.com/apache/airflow/commit/37a7b27242fa06e0c805cbc01cf3cfe3557daf8e>`_  2022-04-26   ``'LookerStartPdtBuildOperator', 'LookerCheckPdtBuildSensor' : fix empty materialization id handling (#23025)``
`967140e6c3 <https://github.com/apache/airflow/commit/967140e6c3bd0f359393e018bf27b7f2310a2fd9>`_  2022-04-25   ``Add location support to BigQueryDataTransferServiceTransferRunSensor.``
`d6094e58ba <https://github.com/apache/airflow/commit/d6094e58ba3e96b54c5480fbffa5f3906222f414>`_  2022-04-25   ``Fix static checks``
`22ea28f23e <https://github.com/apache/airflow/commit/22ea28f23ece16f34597c103d64cab78884a8bf4>`_  2022-04-25   ``Remove run_in_gke_cluster flag``
`c46d04eb2d <https://github.com/apache/airflow/commit/c46d04eb2d62d3bf8a74a4a84c6fad9d12a96792>`_  2022-04-25   ``Create system test for K8s and dataproc operators``
`35cbc89c3a <https://github.com/apache/airflow/commit/35cbc89c3a0a81f462da15b6416453c8323ae486>`_  2022-04-25   ``Create Dataproc operators for GKE``
`27ad3b7827 <https://github.com/apache/airflow/commit/27ad3b7827c5faa116bf43c5530a3d0928fd252d>`_  2022-04-25   ``Remove 'GCSObjectsWtihPrefixExistenceSensor'``
`544d658921 <https://github.com/apache/airflow/commit/544d658921cb2c9ac1abc5a89f2e275255cb924b>`_  2022-04-25   ``Change CloudDatastoreExportEntitiesLink to StorageLink``
`b3cc2f5d10 <https://github.com/apache/airflow/commit/b3cc2f5d102214067c40b3c120364918556e7cca>`_  2022-04-25   ``Fix pre-commit check``
`43ded6c877 <https://github.com/apache/airflow/commit/43ded6c877e90f53e4f5849499a6ed9585b309b7>`_  2022-04-25   ``Add links for Cloud Datastore operators``
`de65a5cc5a <https://github.com/apache/airflow/commit/de65a5cc5acaa1fc87ae8f65d367e101034294a6>`_  2022-04-25   ``Support serviceAccount attr for dataflow in the Apache beam``
`76dc7375b2 <https://github.com/apache/airflow/commit/76dc7375b27976968d37143f7e6dfab1049665f6>`_  2022-04-25   ``Migrate Datastore system tests to new design (AIP-47)``
`0373fb0247 <https://github.com/apache/airflow/commit/0373fb024797bc83be5184886bf94fd4da78a395>`_  2022-04-25   ``'GoogleDriveToGCSOperator': Remove 'destination_bucket' and 'destination_object'``
`6b459995b2 <https://github.com/apache/airflow/commit/6b459995b260cc7023e4720974ef4f59893cd283>`_  2022-04-25   ``Add the format of Vertex Endpoint ID to the docstrings``
`27af0b7ebe <https://github.com/apache/airflow/commit/27af0b7ebe1641d998b890858b0081ccf1472add>`_  2022-04-25   ``Add the new parameter to the docstring``
`48abf571be <https://github.com/apache/airflow/commit/48abf571bec483b0198802e79fb9b948ba41fdd1>`_  2022-04-25   ``Add 'endpoint_id' arg to 'google.cloud.operators.vertex_ai.CreateEndpointOperator'``
`8b6b0848a3 <https://github.com/apache/airflow/commit/8b6b0848a3cacf9999477d6af4d2a87463f03026>`_  2022-04-23   ``Use new Breese for building, pulling and verifying the images. (#23104)``
`07a13bb708 <https://github.com/apache/airflow/commit/07a13bb7088d4a8ba50efbf14981150656b020a7>`_  2022-04-21   ``Change ComputeSSH to throw provider import error instead paramiko (#23035)``
`c36bcc4c06 <https://github.com/apache/airflow/commit/c36bcc4c06c93dce11e2306a4aff66432bffd5a5>`_  2022-04-15   ``Upgrade to support Google Ads v10 (#22965)``
`ea1ae1963e <https://github.com/apache/airflow/commit/ea1ae1963ecf1b543e4f5e8deb59d623df42d44a>`_  2022-04-14   ``Fix cancel_on_kill after execution timeout for DataprocSubmitJobOperator (#22955)``
`9a623e94cb <https://github.com/apache/airflow/commit/9a623e94cb3e4f02cbe566e02f75f4a894edc60d>`_  2022-04-13   ``migrate system test gcs_to_bigquery into new design (#22753)``
`aa317d92ea <https://github.com/apache/airflow/commit/aa317d92ea4dd38fbc27501048ee78b1c0c0aeb5>`_  2022-04-13   ``Fix select * query xcom push for BigQueryGetDataOperator (#22936)``
`27b3e31178 <https://github.com/apache/airflow/commit/27b3e31178a4d64c09c6125bcc69e973275b84be>`_  2022-04-11   ``implements #22859 - Add .sql as templatable extension (#22920)``
`03e1c9b152 <https://github.com/apache/airflow/commit/03e1c9b1521fea46ad3c7e15690810e4548f52c9>`_  2022-04-11   ``MSSQLToGCSOperator fails: datetime is not JSON Serializable (#22882)``
`6933022e94 <https://github.com/apache/airflow/commit/6933022e94acf139b2dea9a589bb8b25c62a5d20>`_  2022-04-10   ``Fix new MyPy errors in main (#22884)``
`6aa65a38e0 <https://github.com/apache/airflow/commit/6aa65a38e0be3fee18ae9c1541e6091a47ab1f76>`_  2022-04-08   ``Add example DAG for demonstrating usage of GCS sensors (#22808)``
=================================================================================================  ===========  ===================================================================================================================================

6.8.0
.....

Latest change: 2022-04-07

=================================================================================================  ===========  ===============================================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ===============================================================================================================================
`56ab82ed7a <https://github.com/apache/airflow/commit/56ab82ed7a5c179d024722ccc697b740b2b93b6a>`_  2022-04-07   ``Prepare mid-April provider documentation. (#22819)``
`838cf401b9 <https://github.com/apache/airflow/commit/838cf401b9a424ad0fbccd5fb8d3040a8f4a7f44>`_  2022-04-06   ``Fail ''LocalFilesystemToGCSOperator'' if src does not exist (#22772)``
`99b0211d50 <https://github.com/apache/airflow/commit/99b0211d5087cf486415b5fc8399d3f15d84ed69>`_  2022-04-04   ``Modify transfer operators to handle more data (#22495)``
`f9e18472c0 <https://github.com/apache/airflow/commit/f9e18472c0c228fc3de7c883c7c3d26d7ee49e81>`_  2022-04-04   ``Add autodetect arg in BQCreateExternalTable Operator (#22710)``
`327eab3e26 <https://github.com/apache/airflow/commit/327eab3e26a3fb3e40a995facebb512cebb0fec2>`_  2022-03-31   ``Add links for BigQuery Data Transfer (#22280)``
`02976bef88 <https://github.com/apache/airflow/commit/02976bef885a5da29a8be59b32af51edbf94466c>`_  2022-03-27   ``Refactor: BigQuery to GCS Operator (#22506)``
`719135ade0 <https://github.com/apache/airflow/commit/719135ade06f4a7017d68dafbd79662a1c1d2948>`_  2022-03-27   ``Remove references to deprecated operators/params in PubSub operators (#22519)``
`ca4b8d1744 <https://github.com/apache/airflow/commit/ca4b8d1744cd1de9b6af97dacb0e03de0f014006>`_  2022-03-27   ``Create Endpoint and Model Service, Batch Prediction and Hyperparameter Tuning Jobs operators for Vertex AI service (#22088)``
`388723950d <https://github.com/apache/airflow/commit/388723950de9ca519108e0a8f6818f0fc0dd91d4>`_  2022-03-27   ``PostgresToGoogleCloudStorageOperator - BigQuery schema type for time zone naive fields (#22536)``
`c063fc688c <https://github.com/apache/airflow/commit/c063fc688cf20c37ed830de5e3dac4a664fd8241>`_  2022-03-25   ``Update black precommit (#22521)``
`3c7cd47319 <https://github.com/apache/airflow/commit/3c7cd4731937652271fc1180a74e9a3af3dd211d>`_  2022-03-25   ``New design of system tests (#22311)``
`7ab45d41d6 <https://github.com/apache/airflow/commit/7ab45d41d6c4de322dc8afe8a74b712d0bae4ee7>`_  2022-03-24   ``Update secrets backends to use get_conn_value instead of get_conn_uri (#22348)``
`d231e9b448 <https://github.com/apache/airflow/commit/d231e9b448d76cd35fd6b6d04305b86a5c5ad94e>`_  2022-03-24   ``Remove coerce_datetime usage from GCSTimeSpanFileTransformOperator (#22501)``
`82a26c0591 <https://github.com/apache/airflow/commit/82a26c05913ef1ac323270363e1cd6d15ee651d2>`_  2022-03-24   ``Fix the docstrings (#22497)``
`38fde2ea79 <https://github.com/apache/airflow/commit/38fde2ea795f69ebd5f4ecc5668e162ce4694ac4>`_  2022-03-23   ``Fix 'download_media' url in 'GoogleDisplayVideo360SDFtoGCSOperator' (#22479)``
`0f0a1a7d22 <https://github.com/apache/airflow/commit/0f0a1a7d22dffab4487c35d3598b3b6aaf24c4c6>`_  2022-03-23   ``Fix to 'CloudBuildRunBuildTriggerOperator' fails to find build id. (#22419)``
=================================================================================================  ===========  ===============================================================================================================================

6.7.0
.....

Latest change: 2022-03-22

=================================================================================================  ===========  ===================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ===================================================================
`d7dbfb7e26 <https://github.com/apache/airflow/commit/d7dbfb7e26a50130d3550e781dc71a5fbcaeb3d2>`_  2022-03-22   ``Add documentation for bugfix release of Providers (#22383)``
`7b851edc91 <https://github.com/apache/airflow/commit/7b851edc916281bb5d3a8358c46b013d6cae84b2>`_  2022-03-21   ``Add 'LocalFilesystemToGoogleDriveOperator' (#22219)``
`14e6b657c2 <https://github.com/apache/airflow/commit/14e6b657c26df6aa3844c4f4531c623cddd143d7>`_  2022-03-21   ``Add timeout and retry to the BigQueryInsertJobOperator (#22395)``
`a3ffbee7c9 <https://github.com/apache/airflow/commit/a3ffbee7c9b5cd8cc5b7b246116f0254f1daa505>`_  2022-03-20   ``Fix skipping non-GCS located jars (#22302)``
`88402038ca <https://github.com/apache/airflow/commit/88402038cac10597a67d3dba6af66eb1bc14377d>`_  2022-03-19   ``Add dataflow_default_options to templated_fields (#22367)``
`6448b2458c <https://github.com/apache/airflow/commit/6448b2458cbeb93c33bfe0ca03261498aa69a186>`_  2022-03-15   ``[FIX] typo doc of gcs operator (#22290)``
=================================================================================================  ===========  ===================================================================

6.6.0
.....

Latest change: 2022-03-14

=================================================================================================  ===========  ==========================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==========================================================================================
`16adc035b1 <https://github.com/apache/airflow/commit/16adc035b1ecdf533f44fbb3e32bea972127bb71>`_  2022-03-14   ``Add documentation for Classifier release for March 2022 (#22226)``
`87c1246b79 <https://github.com/apache/airflow/commit/87c1246b79769f20214a339aadc6a8270d453953>`_  2022-03-14   ``Add Dataplex operators (#20377)``
`c1ab8e2d7b <https://github.com/apache/airflow/commit/c1ab8e2d7b68a31408e750129592e16432474512>`_  2022-03-14   ``Protect against accidental misuse of XCom.get_value() (#22244)``
`c108f264ab <https://github.com/apache/airflow/commit/c108f264abde68e8f458a401296a53ccbe7a47f6>`_  2022-03-13   ``Change the default 'chunk_size' to a clear representation & add documentation (#22222)``
`45435399fe <https://github.com/apache/airflow/commit/45435399fe16c48d11584245a04c357242b23f40>`_  2022-03-13   ``Support Uploading Bigger Files to Google Drive (#22179)``
`42a891d605 <https://github.com/apache/airflow/commit/42a891d6053a9b449909290786c4248c76d4a41f>`_  2022-03-13   ``Update ''GKEDeleteClusterOperator', ''GKECreateClusterOperator'' docstrings (#22212)``
`d08284ed25 <https://github.com/apache/airflow/commit/d08284ed251b7c5712190181623b500a38cd640d>`_  2022-03-11   `` Add map_index to XCom model and interface (#22112)``
`828d1cba4d <https://github.com/apache/airflow/commit/828d1cba4d9b85a166debdd8a8dfe363935c22cd>`_  2022-03-10   ``Add support for ARM platform (#22127)``
`4ac771c316 <https://github.com/apache/airflow/commit/4ac771c3161acb293a39db0ce031bf40d0778803>`_  2022-03-09   ``Fix spelling (#22107)``
`dd0724fdd2 <https://github.com/apache/airflow/commit/dd0724fdd2386576755c5e49d8adb41f0d164116>`_  2022-03-08   ``Add guide for DataprocInstantiateInlineWorkflowTemplateOperator (#22062)``
`dfd9805a23 <https://github.com/apache/airflow/commit/dfd9805a23b2d366f5c332f4cb4131462c5ba82e>`_  2022-03-08   ``Use yaml safe load (#22091)``
`eba9703751 <https://github.com/apache/airflow/commit/eba9703751081d3a7ca8a8754b742fbf12a68bd0>`_  2022-03-08   ``Revert "Use yaml safe load (#22085)" (#22089)``
`7f4935bab3 <https://github.com/apache/airflow/commit/7f4935bab36c41d5927610e38c46a30da2b80906>`_  2022-03-08   ``Use yaml safe load (#22085)``
`a11d831e3f <https://github.com/apache/airflow/commit/a11d831e3f978826d75e62bd70304c5277a8a1ea>`_  2022-03-07   ``Allow for uploading metadata with GCS Hook Upload (#22058)``
=================================================================================================  ===========  ==========================================================================================

6.5.0
.....

Latest change: 2022-03-07

=================================================================================================  ===========  ================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ================================================================================================
`f5b96315fe <https://github.com/apache/airflow/commit/f5b96315fe65b99c0e2542831ff73a3406c4232d>`_  2022-03-07   ``Add documentation for Feb Providers release (#22056)``
`6db9b0029b <https://github.com/apache/airflow/commit/6db9b0029b98611dd748638ab4834a2275e4fa48>`_  2022-03-07   ``Add Looker PDT operators (#20882)``
`9020b3a89d <https://github.com/apache/airflow/commit/9020b3a89d4572572c50d6ac0f1724e09092e0b5>`_  2022-03-06   ``Add autodetect arg to external table creation in GCSToBigQueryOperator (#21944)``
`a0e2ebaa27 <https://github.com/apache/airflow/commit/a0e2ebaa27e5422b7e6ea8d04021fddbbb759bef>`_  2022-03-02   ``Unpin 'google-cloud-memcache' (#21912)``
`84ed747db8 <https://github.com/apache/airflow/commit/84ed747db8e333d2b24ee3a7f59666b89816aa52>`_  2022-03-02   ``Unpin ''pandas-gbq'' and remove unused code (#21915)``
`fb6b2d1fee <https://github.com/apache/airflow/commit/fb6b2d1fee6af366a3311a8012eb35b8f665348a>`_  2022-03-01   ``Make project_id argument optional in all dataproc operators (#21866)``
`08575ddd8a <https://github.com/apache/airflow/commit/08575ddd8a72f96a3439f73e973ee9958188eb83>`_  2022-03-01   ``Change BaseOperatorLink interface to take a ti_key, not a datetime (#21798)``
`6ca118dff1 <https://github.com/apache/airflow/commit/6ca118dff1ede2b1541c43c3738e547b43818f7f>`_  2022-03-01   ``Allow templates in more DataprocUpdateClusterOperator fields (#21865)``
`0c55ca2cda <https://github.com/apache/airflow/commit/0c55ca2cda2433ba79b2f4868361576d41d2b41c>`_  2022-02-28   ``Suppress hook warnings from the Bigquery transfers (#20119)``
`73eb24f25c <https://github.com/apache/airflow/commit/73eb24f25c2d60fb3a2d8fe2ed64b3c165f8d4c6>`_  2022-02-24   ``Fix bigquery_dts parameter docstring typo (#21786)``
`3b4c26eb3a <https://github.com/apache/airflow/commit/3b4c26eb3a1c8d4938be80ab7fa0711561e91f8f>`_  2022-02-23   ``Add Dataproc assets/links (#21756)``
`6061cc4219 <https://github.com/apache/airflow/commit/6061cc42196053e3540d35f5fdcdedf7bb72cb4a>`_  2022-02-20   ``Add Auto ML operators for Vertex AI service (#21470)``
`295efd36ea <https://github.com/apache/airflow/commit/295efd36eac074578e4b54a69d71c2924984326d>`_  2022-02-17   ``Dataflow Assets (#21639)``
`af2c047320 <https://github.com/apache/airflow/commit/af2c047320c5f0742f466943c171ec761d275bab>`_  2022-02-16   ``Add GoogleCalendarToGCSOperator (#20769)``
`1b568d73e1 <https://github.com/apache/airflow/commit/1b568d73e1dfb838a3a0446e3a6063b9f27f04b8>`_  2022-02-15   ``Extract ClientInfo to module level (#21554)``
`dc03000de8 <https://github.com/apache/airflow/commit/dc03000de80e672de661c84f5fbb916413211550>`_  2022-02-15   ``Datafusion assets (#21518)``
`56365b102c <https://github.com/apache/airflow/commit/56365b102c0b0850f27a64fe9b08da4e07fedee1>`_  2022-02-15   ``Dataproc metastore assets (#21267)``
`6692e9191d <https://github.com/apache/airflow/commit/6692e9191df61c8637adbfa249ebbf9882dbba5d>`_  2022-02-15   ``Normalize *_conn_id parameters in BigQuery sensors (#21430)``
`2eb10565b2 <https://github.com/apache/airflow/commit/2eb10565b2075d89eb283bd53462c00f5d54ab55>`_  2022-02-15   ``Fixed PostgresToGCSOperator fail on empty resultset for use_server_side_cursor=True (#21307)``
`da1e6578e0 <https://github.com/apache/airflow/commit/da1e6578e0207b7f2acab794ed3c5bf730719bf8>`_  2022-02-15   ``Fix multi query scenario in bigquery example DAG (#21575)``
=================================================================================================  ===========  ================================================================================================

6.4.0
.....

Latest change: 2022-02-14

=================================================================================================  ===========  ============================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ============================================================================================
`28378d867a <https://github.com/apache/airflow/commit/28378d867afaac497529bd2e1d2c878edf66f460>`_  2022-02-14   ``Add documentation for RC3 release of providers for Jan 2022 (#21553)``
`6bb0857df9 <https://github.com/apache/airflow/commit/6bb0857df94c0f959e7ebe421a00b942fd60b199>`_  2022-02-13   ``(providers_google) add a location check in bigquery (#19571)``
`6579648af2 <https://github.com/apache/airflow/commit/6579648af2a21aa01cb93f051d091569a03c04a4>`_  2022-02-13   ``Fix bigquery-hook when no  engine_kwargs are passed``
`da485da29a <https://github.com/apache/airflow/commit/da485da29a06ecdda720a7ba75f04a2680aac0a2>`_  2022-02-13   ``Add support for BeamGoPipelineOperator (#20386)``
`05a883b35e <https://github.com/apache/airflow/commit/05a883b35e34853ec9326bd579551a8e161d6cdc>`_  2022-02-11   ``Google Cloud Composer opearators (#21251)``
`833087f4f9 <https://github.com/apache/airflow/commit/833087f4f9e86ee063d6a754593d80e9e5cd4100>`_  2022-02-10   ``Enable asynchronous job submission in BigQuery hook (#21385)``
`51aff276ca <https://github.com/apache/airflow/commit/51aff276ca4a33ee70326dd9eea6fba59f1463a3>`_  2022-02-10   ``Optionally raise an error if source file does not exist in GCSToGCSOperator (#21391)``
`07fe9e8c6a <https://github.com/apache/airflow/commit/07fe9e8c6acf8826ac1dcaf2ad8c94297a0f0c24>`_  2022-02-09   ``Never set DagRun.state to State.NONE (#21263)``
`0a3ff43d41 <https://github.com/apache/airflow/commit/0a3ff43d41d33d05fb3996e61785919effa9a2fa>`_  2022-02-08   ``Add pre-commit check for docstring param types (#21398)``
`d94fa37830 <https://github.com/apache/airflow/commit/d94fa378305957358b910cfb1fe7cb14bc793804>`_  2022-02-08   ``Fixed changelog for January 2022 (delayed) provider's release (#21439)``
`e973740208 <https://github.com/apache/airflow/commit/e9737402081aa9c9bac748de1d75b387b3b8da42>`_  2022-02-08   ``Create CustomJob and Datasets operators for Vertex AI service (#21253)``
`34d63fabc0 <https://github.com/apache/airflow/commit/34d63fabc0f2a85df38a78a89f9929e110951d11>`_  2022-02-08   ``Fix BigQueryDataTransferServiceHook.get_transfer_run() request parameter (#21293)``
`6b88d432d9 <https://github.com/apache/airflow/commit/6b88d432d959df73433528fe3d62194239f13edd>`_  2022-02-06   ``Support to upload file to Google Shared Drive (#21319)``
`1a77bc6481 <https://github.com/apache/airflow/commit/1a77bc6481580ab6817267b6e075634caaa025be>`_  2022-02-06   ``:bug: (BigQueryHook) fix compatibility with sqlalchemy engine (#19508)``
`6c3a67d4fc <https://github.com/apache/airflow/commit/6c3a67d4fccafe4ab6cd9ec8c7bacf2677f17038>`_  2022-02-05   ``Add documentation for January 2021 providers release (#21257)``
`39e395f981 <https://github.com/apache/airflow/commit/39e395f9816c04ef2f033eb0b4f635fc3018d803>`_  2022-02-04   ``Add more SQL template fields renderers (#21237)``
`e840acf8d1 <https://github.com/apache/airflow/commit/e840acf8d1840761b72b596ccd4280efece0c974>`_  2022-02-04   ``Fix BigQuery system test (#21320)``
`ddb5246bd1 <https://github.com/apache/airflow/commit/ddb5246bd1576e2ce6abf8c80c3328d7d71a75ce>`_  2022-02-03   ``Refactor operator links to not create ad hoc TaskInstances (#21285)``
`1d4b709e20 <https://github.com/apache/airflow/commit/1d4b709e20b07c6f0b5d1bab1935e19557df2913>`_  2022-01-28   ``Revert "Create CustomJob and Datasets operators for Vertex AI service (#20077)" (#21203)``
`48d44b885b <https://github.com/apache/airflow/commit/48d44b885b0b205a8a4f8ff864716127476ff7f4>`_  2022-01-28   ``Cloudsql import links fix. (#21199)``
`640c0b6763 <https://github.com/apache/airflow/commit/640c0b67631c5f2c8ee866b0726fa7a8a452cd3c>`_  2022-01-28   ``Create CustomJob and Datasets operators for Vertex AI service (#20077)``
`cb73053211 <https://github.com/apache/airflow/commit/cb73053211367e2c2dd76d5279cdc7dc7b190124>`_  2022-01-27   ``Add optional features in providers. (#21074)``
`60aa518ebf <https://github.com/apache/airflow/commit/60aa518ebfe8d794ee216c8283cba841d6510189>`_  2022-01-26   ``batch as templated field in DataprocCreateBatchOperator (#20905)``
`623163f16a <https://github.com/apache/airflow/commit/623163f16ad2bbdd47d499e423fd5e37d36a028b>`_  2022-01-25   ``Extend dataproc example dag (#21091)``
`86ef016eab <https://github.com/apache/airflow/commit/86ef016eabd90819163503ef07c0da50373142ad>`_  2022-01-23   ``Make timeout Optional for wait_for_operation (#20981)``
`506efb6fa3 <https://github.com/apache/airflow/commit/506efb6fa3999ac21a8539e863d81dc684abe52a>`_  2022-01-21   ``Squelch more deprecation warnings (#21003)``
`372849486c <https://github.com/apache/airflow/commit/372849486cd455a4ff4821b01805a442f1a78417>`_  2022-01-21   ``Fix last google provider MyPy errors (#21010)``
`73c0d241d8 <https://github.com/apache/airflow/commit/73c0d241d804507abc651a365f93d60c543349d5>`_  2022-01-21   ``Remove a few stray ':type's in docs (#21014)``
`602abe8394 <https://github.com/apache/airflow/commit/602abe8394fafe7de54df7e73af56de848cdf617>`_  2022-01-20   ``Remove ':type' lines now sphinx-autoapi supports typehints (#20951)``
`b8526abc2c <https://github.com/apache/airflow/commit/b8526abc2c220b1e07eed83694dfee972c2e2609>`_  2022-01-19   ``Add encoding parameter to 'GCSToLocalFilesystemOperator' to fix #20901 (#20919)``
`58452f97db <https://github.com/apache/airflow/commit/58452f97dbcddb4c57a021e9c7fc76139aa9633b>`_  2022-01-03   ``Add hook for integrating with Google Calendar (#20542)``
=================================================================================================  ===========  ============================================================================================

6.3.0
.....

Latest change: 2021-12-31

=================================================================================================  ===========  =====================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =====================================================================================
`f77417eb0d <https://github.com/apache/airflow/commit/f77417eb0d3f12e4849d80645325c02a48829278>`_  2021-12-31   ``Fix K8S changelog to be PyPI-compatible (#20614)``
`97496ba2b4 <https://github.com/apache/airflow/commit/97496ba2b41063fa24393c58c5c648a0cdb5a7f8>`_  2021-12-31   ``Update documentation for provider December 2021 release (#20523)``
`a22d5bd076 <https://github.com/apache/airflow/commit/a22d5bd07696d9cafe10a3e246ea9f3a381585ee>`_  2021-12-31   ``Fix mypy errors in Google Cloud provider (#20611)``
`4233ebe5ce <https://github.com/apache/airflow/commit/4233ebe5cea4862dbf16c9d7c72c4fdd11db9774>`_  2021-12-31   ``Fix setting of project ID in ''provide_authorized_gcloud'' (#20428)``
`83f8e178ba <https://github.com/apache/airflow/commit/83f8e178ba7a3d4ca012c831a5bfc2cade9e812d>`_  2021-12-31   ``Even more typing in operators (template_fields/ext) (#20608)``
`746ee587da <https://github.com/apache/airflow/commit/746ee587da485acdc816129fe71df23e4f024e0b>`_  2021-12-31   ``Delete pods by default in KubernetesPodOperator (#20575)``
`41dbe2c4fc <https://github.com/apache/airflow/commit/41dbe2c4fcfe39c7f5fb5a4b8a341561dd7e3cc1>`_  2021-12-30   ``Fix mypy errors in google/cloud/operators/stackdriver (#20601)``
`dda688776c <https://github.com/apache/airflow/commit/dda688776c196eea708abfda0462af6c92809031>`_  2021-12-30   ``Fix Google mlengine MyPy errors (#20569)``
`d56e7b56bb <https://github.com/apache/airflow/commit/d56e7b56bb9827daaf8890557147fd10bdf72a7e>`_  2021-12-30   ``Fix template_fields type to have MyPy friendly Sequence type (#20571)``
`bd9e8cef26 <https://github.com/apache/airflow/commit/bd9e8cef2687de0b047003e159fd8f3f08c6c61f>`_  2021-12-30   ``Fix Google Mypy Dataproc errors (#20570)``
`a6e60ce25d <https://github.com/apache/airflow/commit/a6e60ce25d9f3d621a7b4089834ca5e50cd123db>`_  2021-12-30   ``Change download_video parameter to resourceName (#20528)``
`af4a2b0240 <https://github.com/apache/airflow/commit/af4a2b0240fbf79a0a6774a9662243050e8fea9c>`_  2021-12-30   ``Fix big query to mssql/mysql transfer issues (#20001)``
`a0821235fb <https://github.com/apache/airflow/commit/a0821235fb6877a471973295fe42283ef452abf6>`_  2021-12-30   ``Use typed Context EVERYWHERE (#20565)``
`da88ed1943 <https://github.com/apache/airflow/commit/da88ed1943e85850fcdf32c663ec2940c65dbe75>`_  2021-12-29   ``Fix MyPy errors in Google Cloud (again) (#20469)``
`3a480f5ff4 <https://github.com/apache/airflow/commit/3a480f5ff41c2da4ae4fd6b2289e064ee42048a5>`_  2021-12-29   ``Fix passing the gzip compression parameter on sftp_to_gcs. (#20553)``
`bfd6d45cec <https://github.com/apache/airflow/commit/bfd6d45cecbc7714cea8e2ce5d8920bdb4819887>`_  2021-12-29   ``switch to follow_redirects on httpx.get call in CloudSQL provider (#20239)``
`7d4d38b546 <https://github.com/apache/airflow/commit/7d4d38b546c44287f8a9d09c4fc141cbea736511>`_  2021-12-29   ``avoid deprecation warnings in BigQuery transfer operators (#20502)``
`b7086f9815 <https://github.com/apache/airflow/commit/b7086f9815d3856cb4f3ee5bbc78657f19df9d2d>`_  2021-12-28   ``Use Python3.7+ syntax in pyupgrade (#20501)``
`a4622e19fa <https://github.com/apache/airflow/commit/a4622e19fa0edc983cb0b29ca6a92969d0cb46fd>`_  2021-12-22   ``Support regional GKE cluster (#18966)``
`2ffdcf4b41 <https://github.com/apache/airflow/commit/2ffdcf4b41158b21e5a08314691d4159dbd44dcb>`_  2021-12-21   ``Fixes docstring for PubSubCreateSubscriptionOperator (#20237)``
`d4c4f9e09e <https://github.com/apache/airflow/commit/d4c4f9e09ee8b0453ff8503c30274eeaa80e7fde>`_  2021-12-21   ``Fix mypy errors for google.cloud_build (#20234)``
`c6dbb3f885 <https://github.com/apache/airflow/commit/c6dbb3f8856be75ff2619476ab3ca587a52e033a>`_  2021-12-21   ``Fix MyPy for Google Bigquery (#20329)``
`ed604b62f3 <https://github.com/apache/airflow/commit/ed604b62f3dfb4d76d6f1eaf4d639dc65956d8f2>`_  2021-12-18   ``Fix remaining MyPy errors in Google Provider (#20358)``
`17404f1f10 <https://github.com/apache/airflow/commit/17404f1f10efd41f98eb8a0317b578ff40f9c77d>`_  2021-12-16   ``Move source_objects datatype check out of GCSToBigQueryOperator.__init__ (#20347)``
`174681911f <https://github.com/apache/airflow/commit/174681911f96f17d41a4f560ca08d5e200944f7f>`_  2021-12-16   ``Fix MyPy Errors for dataproc package (#20327)``
`2fb5e1d0ec <https://github.com/apache/airflow/commit/2fb5e1d0ec306839a3ff21d0bddbde1d022ee8c7>`_  2021-12-15   ``Fix cached_property MyPy declaration and related MyPy errors (#20226)``
`21b8661886 <https://github.com/apache/airflow/commit/21b866188662b08bac0de778daec83cb28864097>`_  2021-12-15   ``Fix missing get_backup method for Dataproc Metastore (#20326)``
`cdaa9a2529 <https://github.com/apache/airflow/commit/cdaa9a252900091f4c0e912a6d2a8890b7cb571a>`_  2021-12-15   ``Fix MyPy errors for google.cloud.tasks (#20233)``
`43efde6230 <https://github.com/apache/airflow/commit/43efde6230487b003f715e04d195126f63f261ff>`_  2021-12-15   ``Fix MyPy Errors for Apache Beam (and Dataflow) provider. (#20301)``
`c4b3694101 <https://github.com/apache/airflow/commit/c4b369410155dfc461d2b95ee66cb1927f8e4230>`_  2021-12-15   ``Fix MyPy errors in leveldb (#20222)``
`1570519a97 <https://github.com/apache/airflow/commit/1570519a976dfb9de1aba9c2c0bee169e7ab5ee1>`_  2021-12-14   ``Fix MyPy errors for google.cloud.transfers (#20229)``
`632bd0133e <https://github.com/apache/airflow/commit/632bd0133e0920c036f1cd83d100f477726fcb41>`_  2021-12-13   ``Fix MyPY errors for google.cloud.example_dags (#20232)``
`644051abcb <https://github.com/apache/airflow/commit/644051abcbb87aab906e050eacce3a70379060dd>`_  2021-12-13   ``Fix MyPy errors for google/marketing_platform and suite (#20227)``
`a208463802 <https://github.com/apache/airflow/commit/a2084638020613979fa1ed9ba944050f274bb160>`_  2021-12-13   ``Organize S3 Classes in Amazon Provider (#20167)``
`98514cc159 <https://github.com/apache/airflow/commit/98514cc1599751d7611b3180c60887da0a25ff5e>`_  2021-12-13   ``Add optional location to bigquery data transfer service (#15088) (#20221)``
`1f662571b2 <https://github.com/apache/airflow/commit/1f662571b2133df09da22aea35936bb10b8ebffa>`_  2021-12-12   ``Fix MyPy errors in google.cloud.sensors (#20228)``
`22341b90da <https://github.com/apache/airflow/commit/22341b90da1d7efb0d9c1d6c4dc054e0238d1f27>`_  2021-12-11   ``Add Google Cloud Tasks how-to documentation (#20145)``
`e9262752dc <https://github.com/apache/airflow/commit/e9262752dce86225e960b420287a51c532b21107>`_  2021-12-11   ``Finalised Datastore documentation (#20138)``
`fa96b09395 <https://github.com/apache/airflow/commit/fa96b093952f96449d6d328a2b9e9300b81cf08e>`_  2021-12-09   ``Update Sphinx and Sphinx-AutoAPI (#20079)``
`ed8b63ba24 <https://github.com/apache/airflow/commit/ed8b63ba2460f47744f4dcf40019592816bb89b5>`_  2021-12-08   ``Providers facebook hook multiple account (#19377)``
`50bf536656 <https://github.com/apache/airflow/commit/50bf5366564957cc0f057ca923317c421fffdeaa>`_  2021-12-08   ``Remove deprecated method call (blob.download_as_string) (#20091)``
`564fe635bd <https://github.com/apache/airflow/commit/564fe635bdb0ba0b26a7b55f63fbe92d4f173e9d>`_  2021-12-06   ``Added example DAG for MSSQL to Google Cloud Storage (GCS) (#19873)``
`cb082d361a <https://github.com/apache/airflow/commit/cb082d361a61da7040e044ff2c1f7758142a9b2d>`_  2021-12-02   ``Remove deprecated template_fields from GoogleDriveToGCSOperator (#19991)``
`6977c47572 <https://github.com/apache/airflow/commit/6977c475720aa18889cd11117a0135e857f2efca>`_  2021-12-01   ``BigQueryHook fix typo in run_load doc string (#19924)``
`f6dca1fa5e <https://github.com/apache/airflow/commit/f6dca1fa5e70ef08798adeb5a6bfc70f41229646>`_  2021-12-01   ``Update doc reference links (#19909)``
=================================================================================================  ===========  =====================================================================================

6.2.0
.....

Latest change: 2021-11-30

=================================================================================================  ===========  ========================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ========================================================================================================
`853576d901 <https://github.com/apache/airflow/commit/853576d9019d2aca8de1d9c587c883dcbe95b46a>`_  2021-11-30   ``Update documentation for November 2021 provider's release (#19882)``
`fb478c00cd <https://github.com/apache/airflow/commit/fb478c00cdc5e78d5e85fe5ac103707c829be2fb>`_  2021-11-28   ``Move 'bucket_name' validation out of '__init__' in Google Marketing Platform operators (#19383)``
`e9e530979a <https://github.com/apache/airflow/commit/e9e530979a9176fa6842a2365ce3ff1bb42dfae2>`_  2021-11-28   ``Update 'default_args' value in example_functions DAG from str to int (#19865)``
`bf68b9a846 <https://github.com/apache/airflow/commit/bf68b9a8461eda634a7d91aa56575fb950960eaa>`_  2021-11-26   ``Create dataproc serverless spark batches operator (#19248)``
`a192cecf6b <https://github.com/apache/airflow/commit/a192cecf6bb9b22e058b8c0015c351131185282b>`_  2021-11-26   ``updates pipeline_timeout CloudDataFusionStartPipelineOperator (#18773)``
`eb163c81d1 <https://github.com/apache/airflow/commit/eb163c81d16532252d6196fd70c85e7ea6236279>`_  2021-11-25   ``Fix GCS system tests (#19227)``
`744d11bdb2 <https://github.com/apache/airflow/commit/744d11bdb2acd52794a959572695943df8729a37>`_  2021-11-25   ``Clean up ''default_args'' usage in docs (#19803)``
`0b2e1a8744 <https://github.com/apache/airflow/commit/0b2e1a8744ac0d5965cb11f6a6fa74cee1d03f3d>`_  2021-11-22   ``Added wait mechanizm to the DataprocJobSensor to avoid 509 errors when Job is not available (#19740)``
`3336bb6c3c <https://github.com/apache/airflow/commit/3336bb6c3cfeea3f5fe9c17f3958db47cc867f61>`_  2021-11-19   ``Fix badly merged impersonation in GKEPodOperator (#19696)``
`952ef908bc <https://github.com/apache/airflow/commit/952ef908bc8965641865aaeee9fbcd52a76d700b>`_  2021-11-19   ``Support impersonation_chain parameter in the GKEStartPodOperator (#19518)``
`853c16465a <https://github.com/apache/airflow/commit/853c16465a4d304a3b7d135356270fee87d3461b>`_  2021-11-18   ``Clean-up of google cloud example dags - batch 3 (#19664)``
`355dec8fea <https://github.com/apache/airflow/commit/355dec8fea5e2ef1a9b88363f201fce4f022fef3>`_  2021-11-17   ``Misc. documentation typos and language improvements (#19599)``
`b9d31cd449 <https://github.com/apache/airflow/commit/b9d31cd44962fc376fcf98380eaa1ea60fb6c835>`_  2021-11-17   ``Cleanup dynamic 'start_date' use for miscellaneous Google example DAGs (#19400)``
`daf234bd5e <https://github.com/apache/airflow/commit/daf234bd5e62d076b9bb861119355ab8c18e27a4>`_  2021-11-16   ``Remove reference to deprecated operator in example_dataproc (#19619)``
`48f228cf9e <https://github.com/apache/airflow/commit/48f228cf9ef7602df9bea6ce20d663ac0c4393e1>`_  2021-11-15   ``#16691 Providing more information in docs for DataprocCreateCluster operator migration (#19446)``
`6ef44b6a50 <https://github.com/apache/airflow/commit/6ef44b6a507a8e8d5f41a6731a0773046623d171>`_  2021-11-15   ``Clean-up of google cloud example dags - batch 2 (#19527)``
`dc0159e7e4 <https://github.com/apache/airflow/commit/dc0159e7e47a7f524ea937634472ffe78d906a16>`_  2021-11-14   ``Add support in GCP connection for reading key from Secret Manager (#19164)``
`4212c49324 <https://github.com/apache/airflow/commit/4212c4932433a50bda09f3e771a02f5ded4553a7>`_  2021-11-14   ``Update Azure modules to comply with AIP-21 (#19431)``
`aa2cb5545f <https://github.com/apache/airflow/commit/aa2cb5545f09d694b9143b323efcd4f6b6c66e60>`_  2021-11-12   ``Remove remaining 'pylint: disable' comments (#19541)``
`c8dc0311da <https://github.com/apache/airflow/commit/c8dc0311dadbcd1b85923a1018e954d979e74d36>`_  2021-11-08   ``Fix Cloud SQL system tests (#19014)``
`26ad55beb0 <https://github.com/apache/airflow/commit/26ad55beb00f5a0915ba4bec541e3d67044834e9>`_  2021-11-08   ``Add dataproc metastore operators (#18945)``
`9efb989d19 <https://github.com/apache/airflow/commit/9efb989d19e657a2cde2eef98804c5007f148ee1>`_  2021-11-07   ``Clean-up of google cloud example dags (#19436)``
`f421409b4d <https://github.com/apache/airflow/commit/f421409b4d431a2055eb273e7bc355819c880bd9>`_  2021-11-05   ``Fix typos in warnings, docstrings, exceptions (#19424)``
`a3c9956f79 <https://github.com/apache/airflow/commit/a3c9956f79310b529a79c1e43fb881c5e173d321>`_  2021-10-30   ``Add support of 'path' parameter for GCloud Storage Transfer Service operators (#17446)``
=================================================================================================  ===========  ========================================================================================================

6.1.0
.....

Latest change: 2021-10-29

=================================================================================================  ===========  ======================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ======================================================================================
`d9567eb106 <https://github.com/apache/airflow/commit/d9567eb106929b21329c01171fd398fbef2dc6c6>`_  2021-10-29   ``Prepare documentation for October Provider's release (#19321)``
`55abc2f620 <https://github.com/apache/airflow/commit/55abc2f620a96832661d1797442a834bf958bb3e>`_  2021-10-28   ``Support query timeout as an argument in CassandraToGCSOperator (#18927)``
`e4aa377da7 <https://github.com/apache/airflow/commit/e4aa377da7fe1801dff04d54c5ed4fd525af94c4>`_  2021-10-28   ``Update BigQueryCreateExternalTableOperator doc and parameters (#18676)``
`20847fdbf8 <https://github.com/apache/airflow/commit/20847fdbf8ecd3be394d24d47ce151c26d018ea1>`_  2021-10-27   ``Add value to "namespaceId" of query (#19163)``
`3c08c025c5 <https://github.com/apache/airflow/commit/3c08c025c5445ffc0533ac28d07ccf2e69a19ca8>`_  2021-10-27   ``Move validation of templated input params to run after the context init (#19048)``
`eba1b68b30 <https://github.com/apache/airflow/commit/eba1b68b30ad2818df0b8fde3be30688ec5c0042>`_  2021-10-27   ``Update dataflow.py (#19231)``
`7ecf29f70d <https://github.com/apache/airflow/commit/7ecf29f70d3fbb1d6174fe693334a0f7fce38a70>`_  2021-10-26   ``Fix hard-coded /tmp directory in CloudSQL Hook (#19229)``
`726a1517ec <https://github.com/apache/airflow/commit/726a1517ec368e0f5906368350d6fa96836943ae>`_  2021-10-26   ``Fix bug in Dataflow hook when no jobs are returned (#18981)``
`d9192a55ba <https://github.com/apache/airflow/commit/d9192a55bacab339c4634f090160bd2d8ed77d7f>`_  2021-10-22   ``Replacing non-attribute template_fields for BigQueryToMsSqlOperator (#19052)``
`4fae04a471 <https://github.com/apache/airflow/commit/4fae04a47119c9f2319ae5e533edcf457e4df003>`_  2021-10-21   ``Upgrade the Dataproc package to 3.0.0 and migrate from v1beta2 to v1 api (#18879)``
`0e95b57772 <https://github.com/apache/airflow/commit/0e95b5777242b00f41812c099f1cf8e2fc0df40c>`_  2021-10-19   ``Google provider catch invalid secret name (#18790)``
`86a2a19ad2 <https://github.com/apache/airflow/commit/86a2a19ad2bdc87a9ad14bb7fde9313b2d7489bb>`_  2021-10-17   ``More f-strings (#18855)``
`a418fd96f7 <https://github.com/apache/airflow/commit/a418fd96f70eac1d4d7dc91553f41d5153beda93>`_  2021-10-17   ``Use google cloud credentials when executing beam command in subprocess (#18992)``
`5c3e453820 <https://github.com/apache/airflow/commit/5c3e4538208cc317e6e45ae7b247e7fb83840f49>`_  2021-10-15   ``Fix BigQueryToMsSqlOperator documentation (#18995)``
`406b38b2e3 <https://github.com/apache/airflow/commit/406b38b2e3fcf9d7fad28573bf77bb9fee5847d1>`_  2021-10-15   ``Replace default api_version of FacebookAdsReportToGcsOperator (#18996)``
`1571f80546 <https://github.com/apache/airflow/commit/1571f80546853688778c2a3ec5194e5c8be0edbd>`_  2021-10-14   ``Add pre-commit hook for common misspelling check in files (#18964)``
`20df60de24 <https://github.com/apache/airflow/commit/20df60de24e1dbeab2dcf5b989b69080d1b3ed34>`_  2021-10-07   ``Dataflow Operators - use project and location from job in on_kill method. (#18699)``
`86bf2a29ba <https://github.com/apache/airflow/commit/86bf2a29ba784b25c335408eb4647ad2eb48b525>`_  2021-10-04   ``Simplify strings previously split across lines (#18679)``
=================================================================================================  ===========  ======================================================================================

6.0.0
.....

Latest change: 2021-09-30

=================================================================================================  ===========  ========================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ========================================================================================
`840ea3efb9 <https://github.com/apache/airflow/commit/840ea3efb9533837e9f36b75fa527a0fbafeb23a>`_  2021-09-30   ``Update documentation for September providers release (#18613)``
`9279c44c91 <https://github.com/apache/airflow/commit/9279c44c91274b7ee31c244d41090c93e5753394>`_  2021-09-29   ``Fix part of Google system tests (#18494)``
`2fadf3c3cf <https://github.com/apache/airflow/commit/2fadf3c3cf6e8a5d26953ebce6401ab5059ee05f>`_  2021-09-27   ``Fix kubernetes engine system test (#18548)``
`a458fcc573 <https://github.com/apache/airflow/commit/a458fcc573845ff65244a2dafd204ed70129f3e8>`_  2021-09-27   ``Updating miscellaneous provider DAGs to use TaskFlow API where applicable (#18278)``
`97d6892318 <https://github.com/apache/airflow/commit/97d6892318ce2866f09f2c21247ed3b1b9975695>`_  2021-09-25   ``Rename AzureDataLakeStorage to ADLS (#18493)``
`a5439eee72 <https://github.com/apache/airflow/commit/a5439eee72cd380f8434e622e8bef7c35786ce39>`_  2021-09-23   ``Add index to the dataset name to have separate dataset for each example DAG (#18459)``
`18d7e1e227 <https://github.com/apache/airflow/commit/18d7e1e2270ffcbc8077ba700f209ae69eccef99>`_  2021-09-21   ``Fix BigQuery system test (#18373)``
`e25eea052f <https://github.com/apache/airflow/commit/e25eea052fd54c94b490a377de05c6bae4c24dbb>`_  2021-09-19   ``Inclusive Language (#18349)``
`7458f1e786 <https://github.com/apache/airflow/commit/7458f1e7861e5146da61cbff9393d72c88a3608c>`_  2021-09-18   ``Remove check for at least one schema in GCSToBigquery (#18150)``
`2474f8922d <https://github.com/apache/airflow/commit/2474f8922d0cb7435040f5e21ca61fb6b633dec2>`_  2021-09-13   ``Migrate Google Cloud Build from Discovery API to Python SDK (#18184)``
`8ae2bb9bfa <https://github.com/apache/airflow/commit/8ae2bb9bfa8cfd62a8ae5f6edabce47800ccb140>`_  2021-09-13   ``Fix error when create external table using table resource (#17998)``
`9140ad8d8f <https://github.com/apache/airflow/commit/9140ad8d8f6dadd56bc592f5cdbf5585c2a8ce89>`_  2021-09-11   ``Use parameters instead of params (#18143)``
`3d4bfdcbb9 <https://github.com/apache/airflow/commit/3d4bfdcbb97c5d68761e5bfd2699a50ca0edd12a>`_  2021-09-10   ``Add missing __init__.py files for some test packages (#18142)``
`cfb602a33d <https://github.com/apache/airflow/commit/cfb602a33dc1904e2f51d74fa711722c8b702726>`_  2021-09-10   ``Fix ''BigQuery'' data extraction in ''BigQueryToMySqlOperator'' (#18073)``
`2fd3f27ebd <https://github.com/apache/airflow/commit/2fd3f27ebd2a4f695968fb7cc5d119e087820928>`_  2021-09-10   ``Make next_dagrun_info take a data interval (#18088)``
`944dcfbb91 <https://github.com/apache/airflow/commit/944dcfbb918050274fd3a1cc51d8fdf460ea2429>`_  2021-09-07   ``Change TaskInstance and TaskReschedule PK from execution_date to run_id (#17719)``
`bfad233b91 <https://github.com/apache/airflow/commit/bfad233b91875fb2dec4217f1b0ae2ba8dd9820c>`_  2021-09-06   ``Fix providers tests in main branch with eager upgrades (#18040)``
`21348c194d <https://github.com/apache/airflow/commit/21348c194d4149237e357e0fff9ed444d27fa71d>`_  2021-09-03   ``fix(CloudSqlProxyRunner): don't query connections from Airflow DB (#18006)``
`9a0c10ba3f <https://github.com/apache/airflow/commit/9a0c10ba3fac3bb88f4f103114d4590b3fb191cb>`_  2021-09-01   ``deduplicate running jobs on BigQueryInsertJobOperator (#17496)``
`fe34582fc2 <https://github.com/apache/airflow/commit/fe34582fc2f418b96a5dc5c10b8b6a8b48bdb7ea>`_  2021-09-01   ``New google operator: SQLToGoogleSheetsOperator (#17887)``
`500780651c <https://github.com/apache/airflow/commit/500780651cfef9254d5e365c0de6f8c7af6d05bf>`_  2021-08-31   ``Add possibility to run DAGs from system tests and see DAGs logs (#17868)``
=================================================================================================  ===========  ========================================================================================

5.1.0
.....

Latest change: 2021-08-30

=================================================================================================  ===========  =========================================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =========================================================================================================================
`0a68588479 <https://github.com/apache/airflow/commit/0a68588479e34cf175d744ea77b283d9d78ea71a>`_  2021-08-30   ``Add August 2021 Provider's documentation (#17890)``
`b5da846dd1 <https://github.com/apache/airflow/commit/b5da846dd1f27d798dc7dc4f4227de4418919874>`_  2021-08-30   ``Fix missing Data Fusion sensor integration (#17914)``
`07405e6df4 <https://github.com/apache/airflow/commit/07405e6df4508fbf3e67d879479e2afd37df8421>`_  2021-08-30   ``[AIRFLOW-9300] Add DatafusionPipelineStateSensor and aync option to the CloudDataFusionStartPipelineOperator (#17787)``
`42e13e1a5a <https://github.com/apache/airflow/commit/42e13e1a5a4c97a2085ddf96f7d93e7bf71949b8>`_  2021-08-30   ``Remove all deprecation warnings in providers (#17900)``
`aa5952e58c <https://github.com/apache/airflow/commit/aa5952e58c58cab65f49b9e2db2adf66f17e7599>`_  2021-08-27   ``Gcp ai hyperparameter tuning (#17790)``
`87769db98f <https://github.com/apache/airflow/commit/87769db98f963338855f59cfc440aacf68e008c9>`_  2021-08-27   ``Allow omission of 'initial_node_count' if 'node_pools' is specified (#17820)``
`be75dcd39c <https://github.com/apache/airflow/commit/be75dcd39cd10264048c86e74110365bd5daf8b7>`_  2021-08-23   ``Update description about the new ''connection-types'' provider meta-data``
`d04aa13526 <https://github.com/apache/airflow/commit/d04aa135268b8e0230be3af6598a3b18e8614c3c>`_  2021-08-20   ``[Airflow 13779] use provided parameters in the wait_for_pipeline_state hook (#17137)``
`76ed2a49c6 <https://github.com/apache/airflow/commit/76ed2a49c6cd285bf59706cf04f39a7444c382c9>`_  2021-08-19   ``Import Hooks lazily individually in providers manager (#17682)``
`b68d1935f9 <https://github.com/apache/airflow/commit/b68d1935f958a480f1e7d8dc1e3415707a14646b>`_  2021-08-19   ``Add error check for config_file parameter in GKEStartPodOperator (#17700)``
`29aab6434f <https://github.com/apache/airflow/commit/29aab6434ffe0fb8c83b6fd6c9e44310966d496a>`_  2021-08-17   ``Adds secrets backend/logging/auth information to provider yaml (#17625)``
`b06d528603 <https://github.com/apache/airflow/commit/b06d52860327cc0a52bcfc4f2305344b3f7c2b1d>`_  2021-08-11   ``Don't cache Google Secret Manager client (#17539)``
`67cbb0f181 <https://github.com/apache/airflow/commit/67cbb0f181f806edb16ca12fb7a2638b5f31eb58>`_  2021-08-02   ``Enable specifying dictionary paths in 'template_fields_renderers' (#17321)``
`c384f9b0f5 <https://github.com/apache/airflow/commit/c384f9b0f509bab704a70380465be18754800a52>`_  2021-07-29   ``GCP Secret Manager error handling for missing credentials (#17264)``
=================================================================================================  ===========  =========================================================================================================================

5.0.0
.....

Latest change: 2021-07-26

=================================================================================================  ===========  =======================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =======================================================================================
`87f408b1e7 <https://github.com/apache/airflow/commit/87f408b1e78968580c760acb275ae5bb042161db>`_  2021-07-26   ``Prepares docs for Rc2 release of July providers (#17116)``
`448e50bd23 <https://github.com/apache/airflow/commit/448e50bd23b4493980a41a5d4241ad3ecef087fb>`_  2021-07-26   ``Updating Google Cloud example DAGs to use XComArgs (#16875)``
`aaf44ccace <https://github.com/apache/airflow/commit/aaf44ccace2336d00240e7e093094a9b808402d9>`_  2021-07-26   ``Updating miscellaneous Google example DAGs to use XComArgs (#16876)``
`d01cc945dd <https://github.com/apache/airflow/commit/d01cc945ddb03620216159335729a36c1a20f9f2>`_  2021-07-26   ``Fixes several failing tests after broken main (#17222)``
`babc4250f3 <https://github.com/apache/airflow/commit/babc4250f3c5420e8d8059d500ba8d0e95d70873>`_  2021-07-26   ``Fixes statich check failures (#17218)``
`5d2224795b <https://github.com/apache/airflow/commit/5d2224795b3548516311025d5549094a9b168f3b>`_  2021-07-25   ``Google Ads Hook: Support newer versions of the google-ads library (#17160)``
`966b250199 <https://github.com/apache/airflow/commit/966b2501995279b7b5f2e1d0bf1c63a511dd382e>`_  2021-07-25   ``Fix GCStoGCS operator with replace diabled and existing destination object (#16991)``
`763919d415 <https://github.com/apache/airflow/commit/763919d4152ffa13433e2489fec85ed286b7b196>`_  2021-07-25   ``Adding custom Salesforce connection type + SalesforceToS3Operator updates (#17162)``
`81bd40933e <https://github.com/apache/airflow/commit/81bd40933ea85a0d7807cf7f9a841157ec885cdf>`_  2021-07-23   ``[CASSANDRA-16814] Fix cassandra to gcs type inconsistency. (#17183)``
`026ffe65d4 <https://github.com/apache/airflow/commit/026ffe65d4738674512f691a56b922e82d0a2309>`_  2021-07-19   ``fix: dataprocpysparkjob project_id as self.project_id (#17075)``
`d02ded65ea <https://github.com/apache/airflow/commit/d02ded65eaa7d2281e249b3fa028605d1b4c52fb>`_  2021-07-15   ``Fixed wrongly escaped characters in amazon's changelog (#17020)``
`b916b75079 <https://github.com/apache/airflow/commit/b916b7507921129dc48d6add1bdc4b923b60c9b9>`_  2021-07-15   ``Prepare documentation for July release of providers. (#17015)``
`a3f5c93806 <https://github.com/apache/airflow/commit/a3f5c93806258b5ad396a638ba0169eca7f9d065>`_  2021-07-13   ``Update alias for field_mask in Google Memmcache (#16975)``
`b0f7f91fe2 <https://github.com/apache/airflow/commit/b0f7f91fe29d1314b71c76de0f11d2dbe81c5c4a>`_  2021-07-07   ``Standardise dataproc location param to region (#16034)``
`866a601b76 <https://github.com/apache/airflow/commit/866a601b76e219b3c043e1dbbc8fb22300866351>`_  2021-06-28   ``Removes pylint from our toolchain (#16682)``
=================================================================================================  ===========  =======================================================================================

4.0.0
.....

Latest change: 2021-06-18

=================================================================================================  ===========  =========================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =========================================================================================
`bbc627a3da <https://github.com/apache/airflow/commit/bbc627a3dab17ba4cf920dd1a26dbed6f5cebfd1>`_  2021-06-18   ``Prepares documentation for rc2 release of Providers (#16501)``
`cbf8001d76 <https://github.com/apache/airflow/commit/cbf8001d7630530773f623a786f9eb319783b33c>`_  2021-06-16   ``Synchronizes updated changelog after buggfix release (#16464)``
`8a9c337838 <https://github.com/apache/airflow/commit/8a9c3378385454f16560d82e885ebc00c5ec069c>`_  2021-06-15   ``Remove class references in changelogs (#16454)``
`1fba5402bb <https://github.com/apache/airflow/commit/1fba5402bb14b3ffa6429fdc683121935f88472f>`_  2021-06-15   ``More documentation update for June providers release (#16405)``
`3c5cc42e13 <https://github.com/apache/airflow/commit/3c5cc42e13322e9b2bc35be73bd04a8d59aa2447>`_  2021-06-14   ``Fix deprecation warnings location in google provider (#16403)``
`b272f9cec9 <https://github.com/apache/airflow/commit/b272f9cec99fd0e3373d23b706f33892cbcb9626>`_  2021-06-13   ``fix: ensure datetime-related values fully compatible with MySQL and BigQuery (#15026)``
`7f8f75eb80 <https://github.com/apache/airflow/commit/7f8f75eb80790d4be3167f5e1ffccc669a281d55>`_  2021-06-12   ``Add BigQueryToMsSqlOperator (#15422)``
`0c80a7d411 <https://github.com/apache/airflow/commit/0c80a7d41100bf8d18b661c8286d6056e6d5d2f1>`_  2021-06-11   ``Fixes AzureFileShare connection extras (#16388)``
`9c94b72d44 <https://github.com/apache/airflow/commit/9c94b72d440b18a9e42123d20d48b951712038f9>`_  2021-06-07   ``Updated documentation for June 2021 provider release (#16294)``
`1e647029e4 <https://github.com/apache/airflow/commit/1e647029e469c1bb17e9ad051d0184f3357644c3>`_  2021-06-01   ``Rename the main branch of the Airflow repo to be 'main' (#16149)``
`99d1535287 <https://github.com/apache/airflow/commit/99d1535287df7f8cfced39baff7a08f6fcfdf8ca>`_  2021-05-31   ``Fix: GCS To BigQuery source_object (#16160)``
`e1137523d4 <https://github.com/apache/airflow/commit/e1137523d4e9cb5d5cfe8584963620677a4ad789>`_  2021-05-30   ``Fix: Unnecessary downloads in ''GCSToLocalFilesystemOperator'' (#16171)``
`904709d34f <https://github.com/apache/airflow/commit/904709d34fbe0b6062d72932b72954afe13ec148>`_  2021-05-27   ``Check synctatic correctness for code-snippets (#16005)``
`86768859c6 <https://github.com/apache/airflow/commit/86768859c689bf02ced96e71996a3a30da1b5888>`_  2021-05-26   ``Fix bigquery type error when export format is parquet (#16027)``
`6ae9aeec3f <https://github.com/apache/airflow/commit/6ae9aeec3f866ecfce83945ad1e831be9f8e5ebb>`_  2021-05-26   ``pass wait_for_done parameter down to _DataflowJobsController (#15541)``
`476d0f6e3d <https://github.com/apache/airflow/commit/476d0f6e3d2059f56532cda36cdc51aa86bafb37>`_  2021-05-22   ``Bump pyupgrade v2.13.0 to v2.18.1 (#15991)``
`aa4713e43f <https://github.com/apache/airflow/commit/aa4713e43f92d3e4c68c3ad00e2d44caaf29aafe>`_  2021-05-21   ``Use api version only in GoogleAdsHook not operators (#15266)``
`76a80bb17c <https://github.com/apache/airflow/commit/76a80bb17c9cecbe3767dab471f6a79084c822ea>`_  2021-05-19   ``Move plyvel to google provider extra (#15812)``
`bb115da0b7 <https://github.com/apache/airflow/commit/bb115da0b78036ace5e31e2139c12ca044b3a97d>`_  2021-05-17   ``Get rid of requests as core dependency (#15781)``
`9c8391a13f <https://github.com/apache/airflow/commit/9c8391a13f6ba29749675cf23f2f874f96b0cc8c>`_  2021-05-10   ``Fix spelling (#15699)``
`3711a29e5e <https://github.com/apache/airflow/commit/3711a29e5e253ede4ab12efe5990e83240e8a9a9>`_  2021-05-09   ``Fix argument ordering and type of bucket and object (#15738)``
`a01567c471 <https://github.com/apache/airflow/commit/a01567c47159da8c2824ac5f15629b51f49af958>`_  2021-05-08   ``Fix sql_to_gcs docstring lint error (#15730)``
`f3fada9101 <https://github.com/apache/airflow/commit/f3fada91013f7916b188ceceb0284bc9860d1388>`_  2021-05-07   ``Add short description to BaseSQLToGCSOperator docstring (#15728)``
`37681bca00 <https://github.com/apache/airflow/commit/37681bca0081dd228ac4047c17631867bba7a66f>`_  2021-05-07   ``Auto-apply apply_default decorator (#15667)``
`b8c0fde38a <https://github.com/apache/airflow/commit/b8c0fde38a7df9d00185bf53e9f303b98fd064dc>`_  2021-05-07   ``Add extra links for google dataproc (#10343)``
`3b4fdd0a7a <https://github.com/apache/airflow/commit/3b4fdd0a7a176bfb2e9a17d4627b1d4ed40f1c86>`_  2021-05-06   ``add oracle  connection link (#15632)``
`cf6324e43b <https://github.com/apache/airflow/commit/cf6324e43b2f7c183c3872704733b69d1498cda1>`_  2021-05-04   ``Implement BigQuery Table Schema Update Operator (#15367)``
`0f97a3970d <https://github.com/apache/airflow/commit/0f97a3970d2c652beedbf2fbaa33e2b2bfd69bce>`_  2021-05-04   ``Rename example bucket names to use INVALID BUCKET NAME by default (#15651)``
=================================================================================================  ===========  =========================================================================================

3.0.0
.....

Latest change: 2021-05-01

=================================================================================================  ===========  ====================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ====================================================================================================
`807ad32ce5 <https://github.com/apache/airflow/commit/807ad32ce59e001cb3532d98a05fa7d0d7fabb95>`_  2021-05-01   ``Prepares provider release after PIP 21 compatibility (#15576)``
`814e471d13 <https://github.com/apache/airflow/commit/814e471d137aad68bd64a21d20736e7b88403f97>`_  2021-04-29   ``Update pre-commit checks (#15583)``
`bf2b48174a <https://github.com/apache/airflow/commit/bf2b48174a1ccfe398eefba7f04a5cacac421266>`_  2021-04-27   ``Add Connection Documentation for Providers (#15499)``
`4b031d39e1 <https://github.com/apache/airflow/commit/4b031d39e12110f337151cda6693e2541bf71c2c>`_  2021-04-27   ``Make Airflow code Pylint 2.8 compatible (#15534)``
`e229f3541d <https://github.com/apache/airflow/commit/e229f3541dd764db54785625875a7c5e94225736>`_  2021-04-27   ``Use Pip 21.* to install airflow officially (#15513)``
`71c673e427 <https://github.com/apache/airflow/commit/71c673e427a89cae2a9f3174c32c5c85556d6342>`_  2021-04-22   ``Update Docstrings of Modules with Missing Params (#15391)``
`3b9a91806e <https://github.com/apache/airflow/commit/3b9a91806ea102cc2bc00b545f63f57031f458c9>`_  2021-04-22   ``Bugfix: Fix rendering of ''object_name'' in ''GCSToLocalFilesystemOperator'' (#15487)``
`c5e302030d <https://github.com/apache/airflow/commit/c5e302030de7512a07120f71f388ad1859b26ca2>`_  2021-04-21   ``Fix typo in DataprocCreateClusterOperator (#15462)``
`42a1ca8aab <https://github.com/apache/airflow/commit/42a1ca8aab905a0eb1ffb3da30cef9c76830abff>`_  2021-04-20   ``Fixes wrongly specified path for leveldb hook (#15453)``
`6da36bad2c <https://github.com/apache/airflow/commit/6da36bad2c5c86628284d91ad6de418bae7cd029>`_  2021-04-18   ``[Airflow-15245] - passing custom image family name to the DataProcClusterCreateoperator (#15250)``
`f649905606 <https://github.com/apache/airflow/commit/f6499056069fd2331b121144e67f6c6e95d7ca5b>`_  2021-04-15   ``fix docstring typos (#15392)``
`7bf69edca0 <https://github.com/apache/airflow/commit/7bf69edca0d0622deb171f5a16af754dbcd04ce2>`_  2021-04-08   ``Fix typo in a docstring (#15276)``
=================================================================================================  ===========  ====================================================================================================

2.2.0
.....

Latest change: 2021-04-06

=================================================================================================  ===========  ====================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ====================================================================================
`042be2e4e0 <https://github.com/apache/airflow/commit/042be2e4e06b988f5ba2dc146f53774dabc8b76b>`_  2021-04-06   ``Updated documentation for provider packages before April release (#15236)``
`eae22cec9c <https://github.com/apache/airflow/commit/eae22cec9c87e8dad4d6e8599e45af1bdd452062>`_  2021-04-06   ``Adds 'Trino' provider (with lower memory footprint for tests) (#15187)``
`e49722859b <https://github.com/apache/airflow/commit/e49722859b81cfcdd7e4bb8e8aba4efb049a8590>`_  2021-04-05   ``Updates 3.6 limits for latest versions of a few libraries (#15209)``
`1d641d8f11 <https://github.com/apache/airflow/commit/1d641d8f114660eee18c6246081cfe991bb74baa>`_  2021-04-01   ``update remaining old import paths of operators (#15127)``
`099c490cff <https://github.com/apache/airflow/commit/099c490cffae9556e56e141addcb41e9676e0d8f>`_  2021-03-28   ``Override project in dataprocSubmitJobOperator (#14981)``
`5379698892 <https://github.com/apache/airflow/commit/53796988929d7b5de98cd322fdea9e0a8edec0a1>`_  2021-03-27   ``Improve docstrings for various modules (#15047)``
`a7ca1b3b0b <https://github.com/apache/airflow/commit/a7ca1b3b0bdf0b7677e53be1b11e833714dfbbb4>`_  2021-03-26   ``Fix Sphinx Issues with Docstrings (#14968)``
`a7e144bec8 <https://github.com/apache/airflow/commit/a7e144bec855f6ccf0fa5ae8447894195ffe170f>`_  2021-03-23   ``Google Dataflow Hook to handle no Job Type (#14914)``
`72ea841b4b <https://github.com/apache/airflow/commit/72ea841b4bb439495b0f58e043774d38f701100e>`_  2021-03-22   ``GCS to BigQuery Transfer Operator with Labels and Description parameter (#14881)``
`e172bd0e16 <https://github.com/apache/airflow/commit/e172bd0e16d5b13105734fe9eb8effc44d593c29>`_  2021-03-22   ``Update docstrings to adhere to sphinx standards (#14918)``
`68e4c4dcb0 <https://github.com/apache/airflow/commit/68e4c4dcb0416eb51a7011a3bb040f1e23d7bba8>`_  2021-03-20   ``Remove Backport Providers (#14886)``
`ddc9133d36 <https://github.com/apache/airflow/commit/ddc9133d36f88dbecd260a4f28ac2dec39395edf>`_  2021-03-15   ``Add GCS timespan transform operator (#13996)``
`943baff670 <https://github.com/apache/airflow/commit/943baff6701f9f8591090bf76219571d7f5e2cc5>`_  2021-03-10   ``Add job labels to bigquery check operators. (#14685)``
`6dc24c95e3 <https://github.com/apache/airflow/commit/6dc24c95e3bb46ac42fc80b1948aa79ae6c6fbd1>`_  2021-03-07   ``Fix grammar and remove duplicate words (#14647)``
`e7bb17aeb8 <https://github.com/apache/airflow/commit/e7bb17aeb83b2218620c5320241b0c9f902d74ff>`_  2021-03-06   ``Use built-in 'cached_property' on Python 3.8 where possible (#14606)``
`7daebefd15 <https://github.com/apache/airflow/commit/7daebefd15355b3f1331c6c58f66f3f88d38a10a>`_  2021-03-05   ``Use libyaml C library when available. (#14577)``
`35c9a90292 <https://github.com/apache/airflow/commit/35c9a902929b79cf7cf53ac5b90c3565dddb97dc>`_  2021-03-01   ``Add Google leveldb hook and operator (#13109) (#14105)``
=================================================================================================  ===========  ====================================================================================

2.1.0
.....

Latest change: 2021-02-27

=================================================================================================  ===========  ===============================================================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ===============================================================================================================================================
`589d6dec92 <https://github.com/apache/airflow/commit/589d6dec922565897785bcbc5ac6bb3b973d7f5d>`_  2021-02-27   ``Prepare to release the next wave of providers: (#14487)``
`50a1504c52 <https://github.com/apache/airflow/commit/50a1504c524257e53eff06589b71973cfab5bf54>`_  2021-02-27   ``Fix spellings (#14483)``
`bfef559cf6 <https://github.com/apache/airflow/commit/bfef559cf6138eec3ac77c64289fb1d45133d8be>`_  2021-02-27   ``Corrects order of argument in docstring in GCSHook.download method (#14497)``
`33214d9326 <https://github.com/apache/airflow/commit/33214d9326bb0bb52f06e230895f4f68fc952664>`_  2021-02-26   ``Refactor SQL/BigQuery/Qubole/Druid Check operators (#12677)``
`c281979982 <https://github.com/apache/airflow/commit/c281979982c36f16c4c346c996a0c8d6ca7c630d>`_  2021-02-23   ``Documentation and example dag for CloudDLPDeidentifyContentOperator, GCSObjectExistenceSensor, GCSObjectsWithPrefixExistenceSensor (#14033)``
`ca35bd7f7f <https://github.com/apache/airflow/commit/ca35bd7f7f6bc2fb4f2afd7762114ce262c61941>`_  2021-02-21   ``By default PIP will install all packages in .local folder (#14125)``
`a7e4266d67 <https://github.com/apache/airflow/commit/a7e4266d675d5283cdd34c6451c8ef0f2858a501>`_  2021-02-21   ``Refactor GoogleDriveToGCSOperator to use common methods (#14276)``
`1ab406663e <https://github.com/apache/airflow/commit/1ab406663ead7475ac14644553ac48466777bd78>`_  2021-02-16   ``Add GoogleDriveToLocalOperator (#14191)``
`59c94c679e <https://github.com/apache/airflow/commit/59c94c679e996ab7a75b4feeb1755353f60d030f>`_  2021-02-13   ``Add 'exists_ok' flag to BigQueryCreateEmptyTable(Dataset)Operator (#14026)``
`e31b27d593 <https://github.com/apache/airflow/commit/e31b27d593f7379f38ced34b6e4ce8947b91fcb8>`_  2021-02-13   ``Add materialized view support for BigQuery (#14201)``
`e3bcaa3ba3 <https://github.com/apache/airflow/commit/e3bcaa3ba351234effe52ad380345c4e39003fcb>`_  2021-02-12   ``Correct typo in GCSObjectsWtihPrefixExistenceSensor  (#14179)``
`7faa2d978c <https://github.com/apache/airflow/commit/7faa2d978c3a4e1eb2f7c6a931c9475712015f9f>`_  2021-02-10   ``Add BigQueryUpdateTableOperator (#14149)``
`1da6972165 <https://github.com/apache/airflow/commit/1da69721651455c9108c00ca5f6723d6557524a9>`_  2021-02-10   ``Fixes to dataproc operators and hook (#14086)``
`02288cf2ba <https://github.com/apache/airflow/commit/02288cf2baf590e448cd008f6216ccf8b776a67a>`_  2021-02-10   ``Add param to CloudDataTransferServiceOperator (#14118)``
`7d38645472 <https://github.com/apache/airflow/commit/7d38645472b0502212504b09d85b0e1271d74274>`_  2021-02-09   ``#9803 fix bug in copy operation without wildcard  (#13919)``
`b0c382426c <https://github.com/apache/airflow/commit/b0c382426c943cbf7bd7c09583d9c5d3137413ee>`_  2021-02-07   ``Add gdrive_to_gcs operator, drive sensor, additional functionality to drive hook, and supporting tests (#13982)``
`5d7d46bb33 <https://github.com/apache/airflow/commit/5d7d46bb33c1d529c1549b593ee27bbc7f56ea29>`_  2021-02-05   ``Improve GCSToSFTPOperator paths handling (#11284)``
`10343ec29f <https://github.com/apache/airflow/commit/10343ec29f8f0abc5b932ba26faf49bc63c6bcda>`_  2021-02-05   ``Corrections in docs and tools after releasing provider RCs (#14082)``
=================================================================================================  ===========  ===============================================================================================================================================

2.0.0
.....

Latest change: 2021-02-04

=================================================================================================  ===========  =========================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =========================================================================================
`88bdcfa0df <https://github.com/apache/airflow/commit/88bdcfa0df5bcb4c489486e05826544b428c8f43>`_  2021-02-04   ``Prepare to release a new wave of providers. (#14013)``
`1872d8719d <https://github.com/apache/airflow/commit/1872d8719d24f94aeb1dcba9694837070b9884ca>`_  2021-02-03   ``Add Apache Beam operators (#12814)``
`0e8c77b93a <https://github.com/apache/airflow/commit/0e8c77b93a5ca5ecfdcd1c4bd91f54846fc15d57>`_  2021-02-03   ``Support google-cloud-logging' >=2.0.0 (#13801)``
`833e338323 <https://github.com/apache/airflow/commit/833e3383230e1f6f73f8022ddf439d3d531eff01>`_  2021-02-02   ``Fix four bugs in StackdriverTaskHandler (#13784)``
`d2efb33239 <https://github.com/apache/airflow/commit/d2efb33239d36e58fb69066fd23779724cb11a90>`_  2021-02-02   ``Support google-cloud-monitoring>=2.0.0 (#13769)``
`ac2f72c98d <https://github.com/apache/airflow/commit/ac2f72c98dc0821b33721054588adbf2bb53bb0b>`_  2021-02-01   ``Implement provider versioning tools (#13767)``
`823741cfea <https://github.com/apache/airflow/commit/823741cfea3e7a2584d1e68126db3d6e6739b08f>`_  2021-01-28   ``Improve GCS system test envs (#13946)``
`6d6588fe2b <https://github.com/apache/airflow/commit/6d6588fe2b8bb5fa33e930646d963df3e0530f23>`_  2021-01-28   ``Add Google Cloud Workflows Operators (#13366)``
`810c15ed85 <https://github.com/apache/airflow/commit/810c15ed85d7bcde8d5b8bc44e1cbd4859e29d2e>`_  2021-01-27   ``Fix and improve GCP BigTable hook and system test (#13896)``
`6616617331 <https://github.com/apache/airflow/commit/6616617331bf6e8548bf6391cebb636220c1cc53>`_  2021-01-27   ``Add env variables to PubSub example dag (#13794)``
`f473ca7130 <https://github.com/apache/airflow/commit/f473ca7130f844bc59477674e641b42b80698bb7>`_  2021-01-24   ``Replace 'google_cloud_storage_conn_id' by 'gcp_conn_id' when using 'GCSHook' (#13851)``
`a9ac2b040b <https://github.com/apache/airflow/commit/a9ac2b040b64de1aa5d9c2b9def33334e36a8d22>`_  2021-01-23   ``Switch to f-strings using flynt. (#13732)``
`9592be88e5 <https://github.com/apache/airflow/commit/9592be88e57cc7f59b9eac978292abd4d7692c0b>`_  2021-01-22   ``Fix Google Spanner example dag (#13842)``
`af52fdb511 <https://github.com/apache/airflow/commit/af52fdb51152a72441a44a271e498b1ec20dfd57>`_  2021-01-22   ``Improve environment variables in GCP Dataflow system test (#13841)``
`e7946f1cb7 <https://github.com/apache/airflow/commit/e7946f1cb7c144181443cbcc843d90bd597b09b5>`_  2021-01-22   ``Improve environment variables in GCP Datafusion system test (#13837)``
`61c1d6ec6c <https://github.com/apache/airflow/commit/61c1d6ec6ce638f8ccd76705f69e9474c308389a>`_  2021-01-22   ``Improve environment variables in GCP Memorystore system test (#13833)``
`202f66093a <https://github.com/apache/airflow/commit/202f66093ad12c293f97204b0775bef2b077cd9a>`_  2021-01-22   ``Improve environment variables in GCP Lifeciences system test (#13834)``
`70bf307f38 <https://github.com/apache/airflow/commit/70bf307f3894214c523701940b89ac0b991a3a63>`_  2021-01-21   ``Add How To Guide for Dataflow (#13461)``
`3fd5ef3555 <https://github.com/apache/airflow/commit/3fd5ef355556cf0ad7896bb570bbe4b2eabbf46e>`_  2021-01-21   ``Add missing logos for integrations (#13717)``
`309788e5e2 <https://github.com/apache/airflow/commit/309788e5e2023c598095a4ee00df417d94b6a5df>`_  2021-01-18   ``Refactor DataprocOperators to support google-cloud-dataproc 2.0 (#13256)``
`7ec858c452 <https://github.com/apache/airflow/commit/7ec858c4523b24e7a3d6dd1d49e3813e6eee7dff>`_  2021-01-17   ``updated Google DV360 Hook to fix SDF issue (#13703)``
`ef8617ec9d <https://github.com/apache/airflow/commit/ef8617ec9d6e4b7c433a29bd388f5102a7a17c11>`_  2021-01-14   ``Support google-cloud-tasks>=2.0.0 (#13347)``
`189af54043 <https://github.com/apache/airflow/commit/189af54043a6aa6e7557bda6cf7cfca229d0efd2>`_  2021-01-13   ``Add system tests for Stackdriver operators (#13644)``
`a6f999b62e <https://github.com/apache/airflow/commit/a6f999b62e3c9aeb10ab24342674d3670a8ad259>`_  2021-01-11   ``Support google-cloud-automl >=2.1.0 (#13505)``
`947dbb73bb <https://github.com/apache/airflow/commit/947dbb73bba736eb146f33117545a18fc2fd3c09>`_  2021-01-11   ``Support google-cloud-datacatalog>=3.0.0 (#13534)``
`2fb68342b0 <https://github.com/apache/airflow/commit/2fb68342b01da4cb5d79ac9e5c0f7687d74351f3>`_  2021-01-07   ``Replace deprecated module and operator in example_tasks.py (#13527)``
`003584bbf1 <https://github.com/apache/airflow/commit/003584bbf1d66a3545ad6e6fcdceb0410fc83696>`_  2021-01-05   ``Fix failing backport packages test (#13497)``
`7d1ea4cb10 <https://github.com/apache/airflow/commit/7d1ea4cb102e7d9878eeeaab5b098ae7767b844b>`_  2021-01-05   ``Replace deprecated module and operator in example_tasks.py (#13473)``
`c7d75ad887 <https://github.com/apache/airflow/commit/c7d75ad887cd12d5603563c5fa873c0e2f8975aa>`_  2021-01-05   ``Revert "Support google-cloud-datacatalog 3.0.0 (#13224)" (#13482)``
`feb84057d3 <https://github.com/apache/airflow/commit/feb84057d34b2f64e3b5dcbaae2d3b18f5f564e4>`_  2021-01-04   ``Support google-cloud-datacatalog 3.0.0 (#13224)``
`3a3e739981 <https://github.com/apache/airflow/commit/3a3e7399810fd399d08f136e6936743c16508fc6>`_  2021-01-04   ``Fix insert_all method of BigQueryHook to support tables without schema (#13138)``
`c33d2c06b6 <https://github.com/apache/airflow/commit/c33d2c06b68c8b9a5a36c965ab8be540a2dca967>`_  2021-01-02   ``Fix another pylint c-extension-no-member (#13438)``
`f6518dd6a1 <https://github.com/apache/airflow/commit/f6518dd6a1217d906d863fe13dc37916efd78b3e>`_  2021-01-02   ``Generalize MLEngineStartTrainingJobOperator to custom images (#13318)``
`9de7127083 <https://github.com/apache/airflow/commit/9de71270838ad3cc59043f1ab0bb6ca97af13622>`_  2020-12-31   ``Support google-cloud-bigquery-datatransfer>=3.0.0 (#13337)``
`406181d64a <https://github.com/apache/airflow/commit/406181d64ac32d133523ca52f954bc50a07defc4>`_  2020-12-31   ``Add Parquet data type to BaseSQLToGCSOperator (#13359)``
`295d66f914 <https://github.com/apache/airflow/commit/295d66f91446a69610576d040ba687b38f1c5d0a>`_  2020-12-30   ``Fix Grammar in PIP warning (#13380)``
`13a9747bf1 <https://github.com/apache/airflow/commit/13a9747bf1d92020caa5d4dc825e096ce583f2df>`_  2020-12-28   ``Revert "Support google-cloud-tasks>=2.0.0 (#13334)" (#13341)``
`04ec45f045 <https://github.com/apache/airflow/commit/04ec45f045419ec87432ee285ac0828ab68008c3>`_  2020-12-28   ``Add DataprocCreateWorkflowTemplateOperator (#13338)``
`1f712219fa <https://github.com/apache/airflow/commit/1f712219fa8971d98bc486896603ce8109c42844>`_  2020-12-28   ``Support google-cloud-tasks>=2.0.0 (#13334)``
`f4745c8ce1 <https://github.com/apache/airflow/commit/f4745c8ce1955c28676b5afe129a88a61aa743b9>`_  2020-12-26   ``Fix typo in example (#13321)``
`e9d65bd458 <https://github.com/apache/airflow/commit/e9d65bd4582b083914f2fc1213bea44cf41d1a08>`_  2020-12-24   ``Decode Remote Google Logs (#13115)``
`e7aeacf335 <https://github.com/apache/airflow/commit/e7aeacf335d373007a32ac65680ba6b5b19f5c9f>`_  2020-12-24   ``Add OracleToGCS Transfer (#13246)``
`323084e97d <https://github.com/apache/airflow/commit/323084e97ddacbc5512709bf0cad8f53082d16b0>`_  2020-12-24   ``Add timeout option to gcs hook methods. (#13156)``
`0b626c8042 <https://github.com/apache/airflow/commit/0b626c8042b304a52d6c481fa6eb689d655f33d3>`_  2020-12-22   ``Support google-cloud-redis>=2.0.0 (#13117)``
`9042a58553 <https://github.com/apache/airflow/commit/9042a585539a18953d688fff455438f4061732d1>`_  2020-12-22   ``Add more operators to example DAGs for Cloud Tasks (#13235)``
`8c00ec89b9 <https://github.com/apache/airflow/commit/8c00ec89b97aa6e725379d08c8ff29a01be47e73>`_  2020-12-22   ``Support google-cloud-pubsub>=2.0.0 (#13127)``
`b26b0df5b0 <https://github.com/apache/airflow/commit/b26b0df5b03c4cd826fd7b2dff5771d64e18e6b7>`_  2020-12-22   ``Update compatibility with google-cloud-kms>=2.0 (#13124)``
`9a1d3820d6 <https://github.com/apache/airflow/commit/9a1d3820d6f1373df790da8751f25e723f9ce037>`_  2020-12-22   ``Support google-cloud-datacatalog>=1.0.0 (#13097)``
`f95b1c9c95 <https://github.com/apache/airflow/commit/f95b1c9c95c059e85ad5676daaa191929785fee2>`_  2020-12-21   ``Add regional support to dataproc workflow template operators (#12907)``
`6cf76d7ac0 <https://github.com/apache/airflow/commit/6cf76d7ac01270930de7f105fb26428763ee1d4e>`_  2020-12-18   ``Fix typo in pip upgrade command :( (#13148)``
`23f27c1b1c <https://github.com/apache/airflow/commit/23f27c1b1cdbcb6bb50fd2aa772aeda7151d5634>`_  2020-12-18   ``Add system tests for CloudKMSHook (#13122)``
`cddbf81b12 <https://github.com/apache/airflow/commit/cddbf81b12650ee5905b0f762c1213caa1d3a7ed>`_  2020-12-17   ``Fix Google BigQueryHook method get_schema() (#13136)``
`1259c712a4 <https://github.com/apache/airflow/commit/1259c712a42d69135dc389de88f79942c70079a3>`_  2020-12-17   ``Update compatibility with google-cloud-os-login>=2.0.0 (#13126)``
`bcf77586ef <https://github.com/apache/airflow/commit/bcf77586eff9907fa057cf2633115d5ab3e4142b>`_  2020-12-16   ``Fix Data Catalog operators (#13096)``
`5090fb0c89 <https://github.com/apache/airflow/commit/5090fb0c8967d2d8719c6f4a468f2151395b5444>`_  2020-12-15   ``Add script to generate integrations.json (#13073)``
`b4b9cf5597 <https://github.com/apache/airflow/commit/b4b9cf55970ca41fa7852ab8d25e59f4c379f8c2>`_  2020-12-14   ``Check for missing references to operator guides (#13059)``
`1c1ef7ee69 <https://github.com/apache/airflow/commit/1c1ef7ee693fead93e269dfd9774a72b6eed2e85>`_  2020-12-14   ``Add project_id to client inside BigQuery hook update_table method (#13018)``
=================================================================================================  ===========  =========================================================================================

1.0.0
.....

Latest change: 2020-12-09

=================================================================================================  ===========  ======================================================================================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ======================================================================================================================================================================
`32971a1a2d <https://github.com/apache/airflow/commit/32971a1a2de1db0b4f7442ed26facdf8d3b7a36f>`_  2020-12-09   ``Updates providers versions to 1.0.0 (#12955)``
`b40dffa085 <https://github.com/apache/airflow/commit/b40dffa08547b610162f8cacfa75847f3c4ca364>`_  2020-12-08   ``Rename remaing modules to match AIP-21 (#12917)``
`9b39f24780 <https://github.com/apache/airflow/commit/9b39f24780e85f859236672e9060b2fbeee81b36>`_  2020-12-08   ``Add support for dynamic connection form fields per provider (#12558)``
`1dcd3e13fd <https://github.com/apache/airflow/commit/1dcd3e13fd0a078fc9440e91b77f6f87aa60dd3b>`_  2020-12-05   ``Add support for extra links coming from the providers (#12472)``
`2037303eef <https://github.com/apache/airflow/commit/2037303eef93fd36ab13746b045d1c1fee6aa143>`_  2020-11-29   ``Adds support for Connection/Hook discovery from providers (#12466)``
`02d94349be <https://github.com/apache/airflow/commit/02d94349be3d201ce9d37d7358573c937fd010df>`_  2020-11-29   ``Don't use time.time() or timezone.utcnow() for duration calculations (#12353)``
`76bcd08dca <https://github.com/apache/airflow/commit/76bcd08dcae8d62307f5e9b8c2e182b54ed22a27>`_  2020-11-28   ``Added '@apply_defaults' decorator. (#12620)``
`e1ebfa68b1 <https://github.com/apache/airflow/commit/e1ebfa68b109b5993c47891cfd0b9b7e46b6d770>`_  2020-11-27   ``Add DataflowJobMessagesSensor and DataflowAutoscalingEventsSensor (#12249)``
`3fa51f94d7 <https://github.com/apache/airflow/commit/3fa51f94d7a17f170ddc31908d36c91f4456a20b>`_  2020-11-24   ``Add check for duplicates in provider.yaml files (#12578)``
`c34ef853c8 <https://github.com/apache/airflow/commit/c34ef853c890e08f5468183c03dc8f3f3ce84af2>`_  2020-11-20   ``Separate out documentation building per provider  (#12444)``
`9e3b2c554d <https://github.com/apache/airflow/commit/9e3b2c554dadf58972198e4e16f15af2f15ec37a>`_  2020-11-19   ``GCP Secrets Optional Lookup (#12360)``
`0080354502 <https://github.com/apache/airflow/commit/00803545023b096b8db4fbd6eb473843096d7ce4>`_  2020-11-18   ``Update provider READMEs for 1.0.0b2 batch release (#12449)``
`7ca0b6f121 <https://github.com/apache/airflow/commit/7ca0b6f121c9cec6e25de130f86a56d7c7fbe38c>`_  2020-11-18   ``Enable Markdownlint rule MD003/heading-style/header-style (#12427) (#12438)``
`8d09506464 <https://github.com/apache/airflow/commit/8d09506464c8480fa42e8bfe6a36c6f631cd23f6>`_  2020-11-18   ``Fix download method in GCSToBigQueryOperator (#12442)``
`2c0920fba5 <https://github.com/apache/airflow/commit/2c0920fba5d2f05d2e29cead91127686af277ec2>`_  2020-11-17   ``Adds mechanism for provider package discovery. (#12383)``
`2cda2f2a0a <https://github.com/apache/airflow/commit/2cda2f2a0a94e5aaed87f0998fa57b4f8bff5e43>`_  2020-11-17   ``Add missing pre-commit definition - provider-yamls (#12393)``
`80a957f142 <https://github.com/apache/airflow/commit/80a957f142f260daed262b8e93a4d02c12cfeabc>`_  2020-11-17   ``Add Dataflow sensors - job metrics (#12039)``
`ae7cb4a1e2 <https://github.com/apache/airflow/commit/ae7cb4a1e2a96351f1976cf5832615e24863e05d>`_  2020-11-17   ``Update wrong commit hash in backport provider changes (#12390)``
`917e6c4424 <https://github.com/apache/airflow/commit/917e6c4424985271c53dd8c413b211896ee55726>`_  2020-11-16   ``Add provide_file_and_upload to GCSHook (#12310)``
`cfa4ecfeb0 <https://github.com/apache/airflow/commit/cfa4ecfeb02661f40b4778733384ac085fb5f04b>`_  2020-11-15   ``Add DataflowJobStatusSensor and support non-blocking execution of jobs (#11726)``
`6889a333cf <https://github.com/apache/airflow/commit/6889a333cff001727eb0a66e375544a28c9a5f03>`_  2020-11-15   ``Improvements for operators and hooks ref docs (#12366)``
`7825e8f590 <https://github.com/apache/airflow/commit/7825e8f59034645ab3247229be83a3aa90baece1>`_  2020-11-13   ``Docs installation improvements (#12304)``
`32b59f8350 <https://github.com/apache/airflow/commit/32b59f8350f55793df6838a32de662a80483ecda>`_  2020-11-12   ``Fixes the sending of an empty list to BigQuery 'list_rows' (#12307)``
`250436d962 <https://github.com/apache/airflow/commit/250436d962c8c950d38c1eb5e54a998891648cc9>`_  2020-11-10   ``Fix spelling in Python files (#12230)``
`502ba309ea <https://github.com/apache/airflow/commit/502ba309ea470943f0e99c634269e3d2d13ce6ca>`_  2020-11-10   ``Enable Markdownlint rule - MD022/blanks-around-headings (#12225)``
`dd2095f4a8 <https://github.com/apache/airflow/commit/dd2095f4a8b07c9b1a4c279a3578cd1e23b71a1b>`_  2020-11-10   ``Simplify string expressions & Use f-string (#12216)``
`f37c6e6fce <https://github.com/apache/airflow/commit/f37c6e6fce8b704f5af28caa16d0ed7d873a0e4a>`_  2020-11-10   ``Add Compute Engine SSH hook (#9879)``
`85a18e13d9 <https://github.com/apache/airflow/commit/85a18e13d9dec84275283ff69e34704b60d54a75>`_  2020-11-09   ``Point at pypi project pages for cross-dependency of provider packages (#12212)``
`59eb5de78c <https://github.com/apache/airflow/commit/59eb5de78c70ee9c7ae6e4cba5c7a2babb8103ca>`_  2020-11-09   ``Update provider READMEs for up-coming 1.0.0beta1 releases (#12206)``
`61feb6ec45 <https://github.com/apache/airflow/commit/61feb6ec453f8dda1a0e1fe3ebcc0f1e3224b634>`_  2020-11-09   ``Provider's readmes generated for elasticsearch and google packages (#12194)``
`b2a28d1590 <https://github.com/apache/airflow/commit/b2a28d1590410630d66966aa1f2b2a049a8c3b32>`_  2020-11-09   ``Moves provider packages scripts to dev (#12082)``
`fcb6b00efe <https://github.com/apache/airflow/commit/fcb6b00efef80c81272a30cfc618202a29e0c6a9>`_  2020-11-08   ``Add authentication to AWS with Google credentials (#12079)``
`2ef3b7ef8c <https://github.com/apache/airflow/commit/2ef3b7ef8cafe3bdc8bf8db70fbc519b98576366>`_  2020-11-08   ``Fix ERROR - Object of type 'bytes' is not JSON serializable when using store_to_xcom_key parameter (#12172)``
`0caec9fd32 <https://github.com/apache/airflow/commit/0caec9fd32bee2b3036b5d7bdcb56bd6a3b9dccf>`_  2020-11-06   ``Dataflow - add waiting for successful job cancel (#11501)``
`cf9437d79f <https://github.com/apache/airflow/commit/cf9437d79f9658d1309e4bfe847fe63d52ec7b99>`_  2020-11-06   ``Simplify string expressions (#12123)``
`91a64db505 <https://github.com/apache/airflow/commit/91a64db505e50712cd53928b4f2b84aece3cc1c0>`_  2020-11-04   ``Format all files (without excepions) by black (#12091)``
`fd3db778e7 <https://github.com/apache/airflow/commit/fd3db778e715d0f164dda7ee8f672d477a323291>`_  2020-11-04   ``Add server side cursor support for postgres to GCS operator (#11793)``
`f1f1940261 <https://github.com/apache/airflow/commit/f1f1940261744b4fdb67b0b5654488494efa9c64>`_  2020-11-04   ``Add DataflowStartSQLQuery operator (#8553)``
`41bf172c1d <https://github.com/apache/airflow/commit/41bf172c1dc75099f4f9d8b3f3350b4b1f523ef9>`_  2020-11-04   ``Simplify string expressions (#12093)``
`5f5244b74d <https://github.com/apache/airflow/commit/5f5244b74df93cadbb99643cec76281460ca4411>`_  2020-11-04   ``Add template fields renderers to Biguery and Dataproc operators (#12067)``
`4e8f9cc8d0 <https://github.com/apache/airflow/commit/4e8f9cc8d02b29c325b8a5a76b4837671bdf5f68>`_  2020-11-03   ``Enable Black - Python Auto Formmatter (#9550)``
`8c42cf1b00 <https://github.com/apache/airflow/commit/8c42cf1b00c90f0d7f11b8a3a455381de8e003c5>`_  2020-11-03   ``Use PyUpgrade to use Python 3.6 features (#11447)``
`45ae145c25 <https://github.com/apache/airflow/commit/45ae145c25a19b4185c33ac0c4da920324b3987e>`_  2020-11-03   ``Log BigQuery job id in insert method of BigQueryHook (#12056)``
`e324b37a67 <https://github.com/apache/airflow/commit/e324b37a67e32c368df50604a00160d7766b5c33>`_  2020-11-03   ``Add job name and progress logs to Cloud Storage Transfer Hook (#12014)``
`6071fdd584 <https://github.com/apache/airflow/commit/6071fdd58470bb2a6c23fc16481e292b7247d0bb>`_  2020-11-02   ``Improve handling server errors in DataprocSubmitJobOperator (#11947)``
`2f703df12d <https://github.com/apache/airflow/commit/2f703df12dfd6511722ff9a82d5a569d092fccc2>`_  2020-10-30   ``Add SalesforceToGcsOperator (#10760)``
`e5713e00b3 <https://github.com/apache/airflow/commit/e5713e00b3afcba6f78006ec0e360da317858e4d>`_  2020-10-29   ``Add drain option when canceling Dataflow pipelines (#11374)``
`37eaac3c5d <https://github.com/apache/airflow/commit/37eaac3c5dc93804413c10a6ca124fd7831befc0>`_  2020-10-29   ``The PRs which are not approved run subset of tests (#11828)``
`79cb771992 <https://github.com/apache/airflow/commit/79cb771992279d40ddd9eb6b0277382313a32898>`_  2020-10-28   ``Fixing re pattern and changing to use a single character class. (#11857)``
`5a439e84eb <https://github.com/apache/airflow/commit/5a439e84eb6c0544dc6c3d6a9f4ceeb2172cd5d0>`_  2020-10-26   ``Prepare providers release 0.0.2a1 (#11855)``
`240c7d4d72 <https://github.com/apache/airflow/commit/240c7d4d72aac8f6aab98f5913e8f54c4f1372ff>`_  2020-10-26   ``Google Memcached hooks - improve protobuf messages handling (#11743)``
`8afdb6ac6a <https://github.com/apache/airflow/commit/8afdb6ac6a7997cb14806bc2734c81c00ed8da97>`_  2020-10-26   ``Fix spellings (#11825)``
`872b1566a1 <https://github.com/apache/airflow/commit/872b1566a11cb73297e657ff325161721b296574>`_  2020-10-25   ``Generated backport providers readmes/setup for 2020.10.29 (#11826)``
`6ce855af11 <https://github.com/apache/airflow/commit/6ce855af118daeaa4c249669079ab9d9aad23945>`_  2020-10-24   ``Fix spelling (#11821)``
`4830687453 <https://github.com/apache/airflow/commit/48306874538eea7cfd42358d5ebb59705204bfc4>`_  2020-10-24   ``Use Python 3 style super classes (#11806)``
`727c739afb <https://github.com/apache/airflow/commit/727c739afb565d4d394a8faedc969334cb8e738e>`_  2020-10-22   ``Improve Cloud Memorystore for Redis example (#11735)``
`1da8379c91 <https://github.com/apache/airflow/commit/1da8379c913843834353b44861c62f332a461bdf>`_  2020-10-22   ``Fix static checks after merging #10121 (#11737)``
`91503308c7 <https://github.com/apache/airflow/commit/91503308c723b186ce6f4026f2a3e2c21030f6e5>`_  2020-10-22   ``Add Google Cloud Memorystore Memcached Operators (#10121)``
`950c16d0b0 <https://github.com/apache/airflow/commit/950c16d0b0ab67bb7af11909de751029faf0313a>`_  2020-10-21   ``Retry requests in case of error in Google ML Engine Hook (#11712)``
`2bfc53b5eb <https://github.com/apache/airflow/commit/2bfc53b5eb67406d418371b74dc9bc5a07be238e>`_  2020-10-21   ``Fix doc errors in google provider files. (#11713)``
`53e6062105 <https://github.com/apache/airflow/commit/53e6062105be0ae1761a354e2055eb0779d12e73>`_  2020-10-21   ``Enforce strict rules for yamllint (#11709)``
`349b0811c3 <https://github.com/apache/airflow/commit/349b0811c3022605426ba57d30936240a7c2848a>`_  2020-10-20   ``Add D200 pydocstyle check (#11688)``
`2d854c3505 <https://github.com/apache/airflow/commit/2d854c3505ccad66e9a7d94267e51bed800433c2>`_  2020-10-19   ``Add service_account to Google ML Engine operator (#11619)``
`46a121fb7b <https://github.com/apache/airflow/commit/46a121fb7b77c0964e053b58750e2d8bc2bd0b2a>`_  2020-10-18   ``docs: Update Bigquery clustering docstrings (#11232)``
`49c58147fe <https://github.com/apache/airflow/commit/49c58147fed8a52869d0b0ecc00c102c11972ad0>`_  2020-10-18   ``Strict type checking for provider Google (#11609)``
`0823d46a7f <https://github.com/apache/airflow/commit/0823d46a7f267f2e45195a175021825367938add>`_  2020-10-16   ``Add type annotations for AWS operators and hooks (#11434)``
`3c10ca6504 <https://github.com/apache/airflow/commit/3c10ca6504be37fabff9a10caefea3fe4df31a02>`_  2020-10-16   ``Add DataflowStartFlexTemplateOperator (#8550)``
`8865d14df4 <https://github.com/apache/airflow/commit/8865d14df4d58dd5f1a4d2ff81c77469959f175a>`_  2020-10-16   ``Strict type checking for provider google cloud  (#11548)``
`16e7129719 <https://github.com/apache/airflow/commit/16e7129719f1c0940aef2a93bed81368e997a746>`_  2020-10-13   ``Added support for provider packages for Airflow 2.0 (#11487)``
`06141d6d01 <https://github.com/apache/airflow/commit/06141d6d01398115e5e54c5766a46ae5514ba2f7>`_  2020-10-12   ``Google cloud operator strict type check (#11450)``
`d305876bee <https://github.com/apache/airflow/commit/d305876bee328287ff391a29cc1cd632468cc731>`_  2020-10-12   ``Remove redundant None provided as default to dict.get() (#11448)``
`1845cd11b7 <https://github.com/apache/airflow/commit/1845cd11b77f302777ab854e84bef9c212c604a0>`_  2020-10-11   ``Strict type check for google ads and cloud hooks (#11390)``
`bd204bb91b <https://github.com/apache/airflow/commit/bd204bb91b4bc069284f9a44757c6baba8884140>`_  2020-10-11   ``Optionally set null marker in csv exports in BaseSQLToGCSOperator (#11409)``
`75071831ba <https://github.com/apache/airflow/commit/75071831baa936d292354f98aac46cd808a4b2b8>`_  2020-10-10   ``Remove redundant parentheses from Python files (#10967)``
`8baf657fc2 <https://github.com/apache/airflow/commit/8baf657fc2b21a601b99b752e4f1176bf8a934ce>`_  2020-10-09   ``Fix regression in DataflowTemplatedJobStartOperator (#11167)``
`b0fcf67559 <https://github.com/apache/airflow/commit/b0fcf675595494b306800e1a516548dc0dc671f8>`_  2020-10-07   ``Add AzureFileShareToGCSOperator (#10991)``
`47b05a87f0 <https://github.com/apache/airflow/commit/47b05a87f004dc273a4757ba49f03808a86f77e7>`_  2020-10-07   ``Improve handling of job_id in BigQuery operators (#11287)``
`0a0e1af800 <https://github.com/apache/airflow/commit/0a0e1af80038ef89974c3c8444461fe867945daa>`_  2020-10-03   ``Fix Broken Markdown links in Providers README TOC (#11249)``
`ca4238eb4d <https://github.com/apache/airflow/commit/ca4238eb4d9a2aef70eb641343f59ee706d27d13>`_  2020-10-02   ``Fixed month in backport packages to October (#11242)``
`5220e4c384 <https://github.com/apache/airflow/commit/5220e4c3848a2d2c81c266ef939709df9ce581c5>`_  2020-10-02   ``Prepare Backport release 2020.09.07 (#11238)``
`cb52fb0ae1 <https://github.com/apache/airflow/commit/cb52fb0ae1de1f1140babaed0e97299e4aaf96bf>`_  2020-09-27   ``Add example DAG and system test for MySQLToGCSOperator (#10990)``
`99accec29d <https://github.com/apache/airflow/commit/99accec29d71b0a57fd4e90151b9d4d10321be07>`_  2020-09-25   ``Fix incorrect Usage of Optional[str] & Optional[int] (#11141)``
`e3f96ce7a8 <https://github.com/apache/airflow/commit/e3f96ce7a8ac098aeef5e9930e6de6c428274d57>`_  2020-09-24   ``Fix incorrect Usage of Optional[bool] (#11138)``
`daf8f31080 <https://github.com/apache/airflow/commit/daf8f31080f06c044b4336071bd383bbbcdc6085>`_  2020-09-23   ``Add template fields renderers for better UI rendering (#11061)``
`f3e87c5030 <https://github.com/apache/airflow/commit/f3e87c503081a3085dff6c7352640d7f08beb5bc>`_  2020-09-22   ``Add D202 pydocstyle check (#11032)``
`cb979f9f21 <https://github.com/apache/airflow/commit/cb979f9f213bb3c9835a3dc924f84a07f5387378>`_  2020-09-22   ``Get Airflow configs with sensitive data from CloudSecretManagerBackend (#11024)``
`76545bb3d6 <https://github.com/apache/airflow/commit/76545bb3d6fa82ce8eae072dbc74a3b76d8fd53c>`_  2020-09-16   ``Add example dag and system test for S3ToGCSOperator (#10951)``
`22c631625f <https://github.com/apache/airflow/commit/22c631625fd68abe280528f33b7cfd7603ebf66c>`_  2020-09-16   ``Fix more docs spellings (#10965)``
`12a652f534 <https://github.com/apache/airflow/commit/12a652f5344c7f03c3d780556ca1829b235fdb2d>`_  2020-09-13   ``Fix parameter name collision in AutoMLBatchPredictOperator #10723 (#10869)``
`41a62735ed <https://github.com/apache/airflow/commit/41a62735edcebbd9c39e505280646ef5d25aa1d5>`_  2020-09-11   ``Add on_kill method to BigQueryInsertJobOperator (#10866)``
`3e91da56e8 <https://github.com/apache/airflow/commit/3e91da56e8c63a90dc859d8996a896b5d9f8cd43>`_  2020-09-11   ``fix typo in firebase/example_filestore DAG (#10875)``
`68cc7273bf <https://github.com/apache/airflow/commit/68cc7273bf0c0f562748b5f663da5c12d2cba6a7>`_  2020-09-10   ``Add on_kill method to DataprocSubmitJobOperator (#10847)``
`f920957214 <https://github.com/apache/airflow/commit/f92095721450c14605c986e165544a7bfb712a3d>`_  2020-09-10   ``Fix and remove some more typos from spelling_wordlist.txt (#10845)``
`9549274d11 <https://github.com/apache/airflow/commit/9549274d110f689a0bd709db829a4d69e274eed9>`_  2020-09-09   ``Upgrade black to 20.8b1 (#10818)``
`078bfaf60a <https://github.com/apache/airflow/commit/078bfaf60adc5aebac8c347e7f6e5339ab9b56c0>`_  2020-09-08   ``Extract missing gcs_to_local example DAG from gcs example (#10767)``
`10ce31127f <https://github.com/apache/airflow/commit/10ce31127f1ff87176158935925afce46a989917>`_  2020-09-08   ``Deprecate using global as the default region in Google Dataproc operators and hooks (#10772)``
`f14f379716 <https://github.com/apache/airflow/commit/f14f3797163cc45fdcdabfb36ee7d638f70e470d>`_  2020-09-07   ``[AIRFLOW-10672] Refactor BigQueryToGCSOperator to use new method (#10773)``
`c8ee455685 <https://github.com/apache/airflow/commit/c8ee4556851c36b3b6e644a7746a49583dd53db1>`_  2020-09-07   ``Refactor DataprocCreateCluster operator to use simpler interface (#10403)``
`ece685b5b8 <https://github.com/apache/airflow/commit/ece685b5b895ad1175440b49bf9e620dffd8248d>`_  2020-09-05   ``Asynchronous execution of Dataproc jobs with a Sensor (#10673)``
`6e3d7b63d3 <https://github.com/apache/airflow/commit/6e3d7b63d3b34c34f8b38a7b41f4a5876e1f731f>`_  2020-09-04   ``Add masterConfig parameter to MLEngineStartTrainingJobOperator (#10578)``
`804548d58f <https://github.com/apache/airflow/commit/804548d58f2036fd4516824a38d0639ba5d5ab0e>`_  2020-09-01   ``Add Dataprep operators (#10304)``
`11c00bc820 <https://github.com/apache/airflow/commit/11c00bc820483691a87cdb16d519dce8dc57c40e>`_  2020-08-30   ``Fix typos: duplicated "the" (#10647)``
`2ca615cffe <https://github.com/apache/airflow/commit/2ca615cffefe97dfa38e1b7f60d9ed33c6628992>`_  2020-08-29   ``Update Google Cloud branding (#10642)``
`1b533f617e <https://github.com/apache/airflow/commit/1b533f617e2e0200597d114d7570f6c0d69da1a0>`_  2020-08-28   ``Fix broken master - DLP (#10635)``
`5ae82a56da <https://github.com/apache/airflow/commit/5ae82a56dab599de44f1be7027cecc4ef86f7bb6>`_  2020-08-28   ``Fix Google DLP example and improve ops idempotency (#10608)``
`3867f76625 <https://github.com/apache/airflow/commit/3867f7662559761864ec4e7be26b776c64c2f199>`_  2020-08-28   ``Update Google Cloud branding (#10615)``
`91ff31ad10 <https://github.com/apache/airflow/commit/91ff31ad1021235bd21c87ad9dbc0b216a908671>`_  2020-08-27   ``Documentation for Google Cloud Data Loss Prevention (#8201) (#9651)``
`fdd9b6f65b <https://github.com/apache/airflow/commit/fdd9b6f65b608c516b8a062b058972d9a45ec9e3>`_  2020-08-25   ``Enable Black on Providers Packages (#10543)``
`d760265452 <https://github.com/apache/airflow/commit/d7602654526fdd2876466371404784bd17cfe0d2>`_  2020-08-25   ``PyDocStyle: No whitespaces allowed surrounding docstring text (#10533)``
`d1bce91bb2 <https://github.com/apache/airflow/commit/d1bce91bb21d5a468fa6a0207156c28fe1ca6513>`_  2020-08-25   ``PyDocStyle: Enable D403: Capitalized first word of docstring (#10530)``
`866701c801 <https://github.com/apache/airflow/commit/866701c8019f49dcb02c9696e4f6e9ce67d13ca6>`_  2020-08-25   ``Fix typo in "Cloud" (#10534)``
`47265e7b58 <https://github.com/apache/airflow/commit/47265e7b58bc28bcbbffc981442b6cc27a3af39c>`_  2020-08-24   ``Fix typo in PostgresHook (#10529)``
`3696c34c28 <https://github.com/apache/airflow/commit/3696c34c28c6bc7b442deab999d9ecba24ed0e34>`_  2020-08-24   ``Fix typo in the word "release" (#10528)``
`2f2d8dbfaf <https://github.com/apache/airflow/commit/2f2d8dbfafefb4be3dd80f22f31c649c8498f148>`_  2020-08-25   ``Remove all "noinspection" comments native to IntelliJ (#10525)``
`3734876d98 <https://github.com/apache/airflow/commit/3734876d9898067ee933b84af522d53df6160d7f>`_  2020-08-24   ``Implement impersonation in google operators (#10052)``
`b0598b5351 <https://github.com/apache/airflow/commit/b0598b5351d2d027286e2333231b6c0c0704dba2>`_  2020-08-24   ``Add support for creating multiple replicated clusters in Bigtable hook and operator (#10475)``
`ee7ca128a1 <https://github.com/apache/airflow/commit/ee7ca128a17937313566f2badb6cc569c614db94>`_  2020-08-22   ``Fix broken Markdown refernces in Providers README (#10483)``
`515cc72c99 <https://github.com/apache/airflow/commit/515cc72c995429c8c007f853ade385d79fcbac90>`_  2020-08-22   ``Fix typo in timed_out (#10459)``
`7c206a82a6 <https://github.com/apache/airflow/commit/7c206a82a6f074abcc4898a005ecd2c84a920054>`_  2020-08-22   ``Replace assigment with Augmented assignment (#10468)``
`88c7d2e526 <https://github.com/apache/airflow/commit/88c7d2e526af4994066f65f830e2fa8edcbbce2e>`_  2020-08-21   ``Dataflow operators don't not always create a virtualenv (#10373)``
`083c3c129b <https://github.com/apache/airflow/commit/083c3c129bc3458d410f5ff37d7f5a9a7ad548b7>`_  2020-08-18   ``Simplified GCSTaskHandler configuration (#10365)``
`1ae5bdf23e <https://github.com/apache/airflow/commit/1ae5bdf23e3ac7cca05325ef8b255a7cf067e18e>`_  2020-08-17   ``Add test for GCSTaskHandler (#9600) (#9861)``
`e195a980bc <https://github.com/apache/airflow/commit/e195a980bc8e9d42f3eb4ac134950977b9e5158f>`_  2020-08-16   ``Add type annotations for mlengine_operator_utils (#10297)``
`382c1011b6 <https://github.com/apache/airflow/commit/382c1011b6bcebd22760e2f98419281ef1a09d1b>`_  2020-08-16   ``Add Bigtable Update Instance Hook/Operator (#10340)``
`bfa5a8d5f1 <https://github.com/apache/airflow/commit/bfa5a8d5f10458c14d380c4042ecfbac627d0639>`_  2020-08-15   ``CI: Fix failing docs-build (#10342)``
`be46d20fb4 <https://github.com/apache/airflow/commit/be46d20fb431cc1d91c935e8894dfc7756c18993>`_  2020-08-15   ``Improve idempotency of BigQueryInsertJobOperator (#9590)``
`47387a69e6 <https://github.com/apache/airflow/commit/47387a69e623676b57b6d42ff07e729da2d21bff>`_  2020-08-14   ``Catch Permission Denied exception when getting secret from GCP Secret Manager. (#10326)``
`2f0613b0c2 <https://github.com/apache/airflow/commit/2f0613b0c2fdf176d9f13a8cd12162c60c64b644>`_  2020-08-13   ``Implement Google BigQuery Table Partition Sensor (#10218)``
`f6734b3b85 <https://github.com/apache/airflow/commit/f6734b3b850d33d3712763f93c114e80f5af9ffb>`_  2020-08-12   ``Enable Sphinx spellcheck for doc generation (#10280)``
`8f8db8959e <https://github.com/apache/airflow/commit/8f8db8959e526be54d700845d36ee9f315bae2ea>`_  2020-08-12   ``DbApiHook: Support kwargs in get_pandas_df (#9730)``
`ef088314f8 <https://github.com/apache/airflow/commit/ef088314f8f1b29ac636a7584cf9dda04b1df816>`_  2020-08-09   ``Added DataprepGetJobsForJobGroupOperator (#10246)``
`b43f90abf4 <https://github.com/apache/airflow/commit/b43f90abf4c7219d5d59cccb0514256bd3f2fdc7>`_  2020-08-09   ``Fix various typos in the repo (#10263)``
`c29533888f <https://github.com/apache/airflow/commit/c29533888fadd40f5e9ce63e728bd8691182e542>`_  2020-08-08   ``Add labels param to Google MLEngine Operators (#10222)``
`cdec301254 <https://github.com/apache/airflow/commit/cdec3012542b45d23a05f62d69110944ba542e2a>`_  2020-08-07   ``Add correct signature to all operators and sensors (#10205)``
`eff0f03210 <https://github.com/apache/airflow/commit/eff0f03210d30a4aed9ed457eaaea9c9f05d54d1>`_  2020-08-06   `` Update guide for Google Cloud Secret Manager Backend (#10172)``
`24c8e4c2d6 <https://github.com/apache/airflow/commit/24c8e4c2d6e359ecc2c7d6275dccc68de4a82832>`_  2020-08-06   ``Changes to all the constructors to remove the args argument (#10163)``
`010322692e <https://github.com/apache/airflow/commit/010322692e6e3f0adc156f0beb81e267da0e97bb>`_  2020-08-06   ``Improve handling Dataproc cluster creation with ERROR state (#9593)``
`1437cb7495 <https://github.com/apache/airflow/commit/1437cb74955f4e10af5d70ebadde1e6b163fb9b7>`_  2020-08-04   ``Add correct signatures for operators in google provider package (#10144)``
`6efa1b9cb7 <https://github.com/apache/airflow/commit/6efa1b9cb763ae0bdbc884a54d24dbdc39d9e3a6>`_  2020-08-03   ``Add additional Cloud Datastore operators (#10032)``
`27020f8e58 <https://github.com/apache/airflow/commit/27020f8e588575d53e63f9f9daecd3a522656644>`_  2020-08-03   ``Add try clause to DataFusionHook.wait_for_pipeline_state (#10031)``
`4e3799fec4 <https://github.com/apache/airflow/commit/4e3799fec4c23d0f43603a0489c5a6158aeba035>`_  2020-08-02   ``[AIRFLOW-4541] Replace os.mkdirs usage with pathlib.Path(path).mkdir (#10117)``
`85c56b1737 <https://github.com/apache/airflow/commit/85c56b1737c2bf61751836571300445c0aebae1a>`_  2020-08-02   ``Add missing params to GCP Pub/Sub creation_subscription (#10106)``
`b79466c12f <https://github.com/apache/airflow/commit/b79466c12f3ae717c31804acc2e9ffcd60f9611c>`_  2020-08-02   ``Fix sensor not providing arguments for GCSHook (#10074)``
`4ee35d0279 <https://github.com/apache/airflow/commit/4ee35d027988c6456767faeb108a7f686d5117f2>`_  2020-08-02   ``Fix hook not passing gcp_conn_id to base class (#10075)``
`aeea71274d <https://github.com/apache/airflow/commit/aeea71274d4527ff2351102e94aa38bda6099e7f>`_  2020-08-02   ``Remove 'args' parameter from provider operator constructors (#10097)``
`4c84661adb <https://github.com/apache/airflow/commit/4c84661adb5bb5c581bb4193b4c7e935cbe07758>`_  2020-07-31   ``Split Display Video 360 example into smaler DAGs (#10077)``
`59cbff0874 <https://github.com/apache/airflow/commit/59cbff0874dd5318cda4b9ce7b7eeb1aad1dad4d>`_  2020-07-29   ``Fix docstrings in BigQueryGetDataOperator (#10042)``
`81b87d48ed <https://github.com/apache/airflow/commit/81b87d48ed002d7a7f7bcb72a58e82d40a176fe2>`_  2020-07-27   ``Add unit tests for GcpBodyFieldSanitizer in Google providers (#9996)``
`7d24b088cd <https://github.com/apache/airflow/commit/7d24b088cd736cfa18f9214e4c9d6ce2d5865f3d>`_  2020-07-25   ``Stop using start_date in default_args in example_dags (2) (#9985)``
`8b10a4b35e <https://github.com/apache/airflow/commit/8b10a4b35e45d536a6475bfe1491ee75fad50186>`_  2020-07-25   ``Stop using start_date in default_args in example_dags (#9982)``
`ef98edf4da <https://github.com/apache/airflow/commit/ef98edf4da2d9b74d5cf5b21e81577b3151edb79>`_  2020-07-23   ``Add more information about using GoogleAdsHook (#9951)``
`33f0cd2657 <https://github.com/apache/airflow/commit/33f0cd2657b2e77ea3477e0c93f13f1474be628e>`_  2020-07-22   ``apply_default keeps the function signature for mypy (#9784)``
`39a0288a47 <https://github.com/apache/airflow/commit/39a0288a47536dfd9b651ecd075887d3e45fcfc4>`_  2020-07-22   ``Add Google Authentication for experimental API (#9848)``
`c2db0dfeb1 <https://github.com/apache/airflow/commit/c2db0dfeb13ee679bf4d7b57874f0fcb39c0f0ed>`_  2020-07-22   ``More strict rules in mypy (#9705) (#9906)``
`c4244e18bb <https://github.com/apache/airflow/commit/c4244e18bb894eb2180b8972052e56110fe5cbc9>`_  2020-07-22   ``Fix calling 'get_client' in BigQueryHook.table_exists (#9916)``
`5eacc16420 <https://github.com/apache/airflow/commit/5eacc164201a121cd06126aff613cbe0919d35cc>`_  2020-07-22   ``Add support for impersonation in GCP hooks (#9915)``
`1cfdebf5f8 <https://github.com/apache/airflow/commit/1cfdebf5f8841d61a11540b88c7913686e89e085>`_  2020-07-21   ``Fix insert_job method of BigQueryHook (#9899)``
`c8c52e69c8 <https://github.com/apache/airflow/commit/c8c52e69c8d9cc1f26f63d95aecc0a6498d40b6f>`_  2020-07-21   ``Remove type hint causing DeprecationWarning in Firestore operators (#9819)``
`eb6f1d1cf0 <https://github.com/apache/airflow/commit/eb6f1d1cf0503fa763c0d8d34a2fe16efb390b9c>`_  2020-07-16   ``Fix typo in datafusion operator (#9859)``
`b01d95ec22 <https://github.com/apache/airflow/commit/b01d95ec22b01ed79123178acd74ef40d57aaa7c>`_  2020-07-15   ``Change DAG.clear to take dag_run_state (#9824)``
`6d65c15d15 <https://github.com/apache/airflow/commit/6d65c15d156a41d5e735e44a1170426559a17d1f>`_  2020-07-15   ``Add guide for AI Platform (previously Machine Learning Engine) Operators  (#9798)``
`770de53eb5 <https://github.com/apache/airflow/commit/770de53eb57bd57ffc555ad15b18f0c058dbebe7>`_  2020-07-15   ``BigQueryTableExistenceSensor needs to specify keyword arguments (#9832)``
`2d8dbacdf6 <https://github.com/apache/airflow/commit/2d8dbacdf6c19a598a7f55bcf65e28703aed6201>`_  2020-07-15   ``Add CloudVisionDeleteReferenceImageOperator  (#9698)``
`9f017951b9 <https://github.com/apache/airflow/commit/9f017951b94d9bf52b5ee66d72aa8dd822f07269>`_  2020-07-15   ``Add Google Deployment Manager Hook (#9159)``
`ed5004cca7 <https://github.com/apache/airflow/commit/ed5004cca753650dc222fbb8e67573938c6c16d9>`_  2020-07-14   ``Allow 'replace' flag in gcs_to_gcs operator. (#9667)``
`553bb7af7c <https://github.com/apache/airflow/commit/553bb7af7cb7a50f7141b5b89297713cee6d19f6>`_  2020-07-13   ``Keep functions signatures in decorators (#9786)``
`68925904e4 <https://github.com/apache/airflow/commit/68925904e49aac6968defb6834863f4e6347fe59>`_  2020-07-13   ``Add multiple file upload functionality to GCS hook (#8849)``
`1de78e8f97 <https://github.com/apache/airflow/commit/1de78e8f97f48f8f4abd167a0120ffab8af6127a>`_  2020-07-12   ``Add Google Stackdriver link (#9765)``
`092d33f298 <https://github.com/apache/airflow/commit/092d33f298a7dbb871b1e1b4c17aad3989e89b79>`_  2020-07-11   ``Fix StackdriverTaskHandler + add system tests (#9761)``
`b2305660f0 <https://github.com/apache/airflow/commit/b2305660f0eb55ebd31fdc7fe4e8aeed8c1f8c00>`_  2020-07-09   ``Update example DAG for AI Platform operators (#9727)``
`23f80f34ad <https://github.com/apache/airflow/commit/23f80f34adec86da24e4896168c53d213d01a7f6>`_  2020-07-08   ``Move gcs & wasb task handlers to their respective provider packages (#9714)``
`44d4ae809c <https://github.com/apache/airflow/commit/44d4ae809c1e3784ff95b6a5e95113c3412e56b3>`_  2020-07-06   ``Upgrade to latest pre-commit checks (#9686)``
`a79e2d4c4a <https://github.com/apache/airflow/commit/a79e2d4c4aa105f3fac5ae6a28e29af9cd572407>`_  2020-07-06   ``Move provider's log task handlers to the provider package (#9604)``
`cd3d9d9340 <https://github.com/apache/airflow/commit/cd3d9d93402f06a08f35e3586802f11a18c4f1f3>`_  2020-07-02   ``Fix using .json template extension in GMP operators (#9566)``
`4799af30ee <https://github.com/apache/airflow/commit/4799af30ee02c596647d1538854769124f9f4961>`_  2020-06-30   ``Extend BigQuery example with include clause (#9572)``
`e33f1a12d7 <https://github.com/apache/airflow/commit/e33f1a12d72ac234e4897f44b326a332acf85901>`_  2020-06-30   ``Add template_ext to BigQueryInsertJobOperator (#9568)``
`40add26d45 <https://github.com/apache/airflow/commit/40add26d459c2511a6d9d305ae7300f0d6104211>`_  2020-06-29   ``Remove almost all references to airflow.contrib (#9559)``
`c420dbd6e1 <https://github.com/apache/airflow/commit/c420dbd6e13e17867eb4ccc4271b37966310ac0f>`_  2020-06-27   ``Bump Pylint to 2.5.3 (#9294)``
`0051c89cba <https://github.com/apache/airflow/commit/0051c89cba02d55236c913ce0110f7d5111ba436>`_  2020-06-26   ``nitpick fix (#9527)``
`87fdbd0708 <https://github.com/apache/airflow/commit/87fdbd0708d942af98d35604fe5962962e25d246>`_  2020-06-25   ``Use literal syntax instead of function calls to create data structure (#9516)``
`7256f4caa2 <https://github.com/apache/airflow/commit/7256f4caa226f8f8632d6e2d38d8c94cb3250a6f>`_  2020-06-22   ``Pylint fixes and deprecation of rare used methods in Connection (#9419)``
`e13a14c873 <https://github.com/apache/airflow/commit/e13a14c8730f4f633d996dd7d3468fe827136a84>`_  2020-06-21   ``Enable & Fix Whitespace related PyDocStyle Checks (#9458)``
`5b680e27e8 <https://github.com/apache/airflow/commit/5b680e27e8118861ef484c00a4b87c6885b0a518>`_  2020-06-19   ``Don't use connection to store task handler credentials (#9381)``
`d0e7db4024 <https://github.com/apache/airflow/commit/d0e7db4024806af35e3c9a2cae460fdeedd4d2ec>`_  2020-06-19   ``Fixed release number for fresh release (#9408)``
`416334e2ec <https://github.com/apache/airflow/commit/416334e2ecd21d8a532af6102f1cfa9ac921a97a>`_  2020-06-19   ``Properly propagated warnings in operators (#9348)``
`12af6a0800 <https://github.com/apache/airflow/commit/12af6a08009b8776e00d8a0aab92363eb8c4e8b1>`_  2020-06-19   ``Final cleanup for 2020.6.23rc1 release preparation (#9404)``
`c7e5bce57f <https://github.com/apache/airflow/commit/c7e5bce57fe7f51cefce4f8a41ce408ac5675d13>`_  2020-06-19   ``Prepare backport release candidate for 2020.6.23rc1 (#9370)``
`4e09c64423 <https://github.com/apache/airflow/commit/4e09c64423bfaabd02a18b5fe7757dc15451ab73>`_  2020-06-18   ``Adds GCP Secret Manager Hook (#9368)``
`40bf8f28f9 <https://github.com/apache/airflow/commit/40bf8f28f97f17f40d993d207ea740eba54593ee>`_  2020-06-18   ``Detect automatically the lack of reference to the guide in the operator descriptions (#9290)``
`f6bd817a3a <https://github.com/apache/airflow/commit/f6bd817a3aac0a16430fc2e3d59c1f17a69a15ac>`_  2020-06-16   ``Introduce 'transfers' packages (#9320)``
`639972d995 <https://github.com/apache/airflow/commit/639972d995d848b16a3f283576efdbde28b8fdef>`_  2020-06-16   ``Add support for latest Apache Beam SDK in Dataflow operators (#9323)``
`1459970b3b <https://github.com/apache/airflow/commit/1459970b3b9780e139ce029ae889fd8f69a37bc7>`_  2020-06-15   ``Rename CloudBuildCreateBuildOperator to CloudBuildCreateOperator (#9314)``
`431ea3291c <https://github.com/apache/airflow/commit/431ea3291c9bf236bccdf8446d753c630ada2b25>`_  2020-06-15   ``Resolve upstream tasks when template field is XComArg (#8805)``
`aee6ab94eb <https://github.com/apache/airflow/commit/aee6ab94eb956347ad560cfe2673bc6011074513>`_  2020-06-15   ``Wait for pipeline state in Data Fusion operators (#8954)``
`fb1c8b83d4 <https://github.com/apache/airflow/commit/fb1c8b83d400506a16c10e3d6623a913847e5cf5>`_  2020-06-10   ``Add test for BQ operations using location (#9206)``
`a26afbfa51 <https://github.com/apache/airflow/commit/a26afbfa51b0981ae742c6171938b57a80aace2b>`_  2020-06-10   ``Make generated job_id more informative in BQ insert_job (#9203)``
`c41192fa1f <https://github.com/apache/airflow/commit/c41192fa1fc5c2b3e7b8414c59f656ab67bbef28>`_  2020-06-10   ``Upgrade pendulum to latest major version ~2.0 (#9184)``
`b1c8c5ed5b <https://github.com/apache/airflow/commit/b1c8c5ed5bba3a852a5446f3fdd1131b4b22637a>`_  2020-06-09   ``Allows using private endpoints in GKEStartPodOperator (#9169)``
`5918efc86a <https://github.com/apache/airflow/commit/5918efc86a2217caa641a6ada289eee1c21407f8>`_  2020-06-05   ``Add 3.8 to the test matrices (#8836)``
`9bcdadaf7e <https://github.com/apache/airflow/commit/9bcdadaf7e6e73d3d2246fbbd32a9f30a1b43ca9>`_  2020-06-05   ``Add 'main' param to template_fields in DataprocSubmitPySparkJobOperator (#9154)``
`f56811dff3 <https://github.com/apache/airflow/commit/f56811dff3af66cbceb0418f11e00507bab58674>`_  2020-06-05   ``[AIRFLOW-6290] Create guide for GKE operators (#8883)``
`76962867b5 <https://github.com/apache/airflow/commit/76962867b5877cf5ffd1b6004453f783c0732ab1>`_  2020-06-04   ``Fix sql_to_gcs hook gzip of schema_file (#9140)``
`17adcea835 <https://github.com/apache/airflow/commit/17adcea835cb7b0cf2d8da0ac7dda5549cfa3e45>`_  2020-06-02   ``Fix handling of subprocess error handling in s3_file_transform and gcs (#9106)``
`7898525468 <https://github.com/apache/airflow/commit/78985254683c359f7444a7eb5f6ee4967c37d61f>`_  2020-06-01   ``Add BigQueryInsertJobOperator (#8868)``
`29eb68b90b <https://github.com/apache/airflow/commit/29eb68b90b5df692ac322be0939af5e7fa9b71bc>`_  2020-05-31   ``Create guide for Dataproc Operators (#9037)``
`886afaf622 <https://github.com/apache/airflow/commit/886afaf622602aa97f925bc3ee4fc27aa995c445>`_  2020-05-29   ``Add example dag and system test for LocalFilesystemToGCSOperator (#9043)``
`a779c4dfc2 <https://github.com/apache/airflow/commit/a779c4dfc278d6ece480b012764ea5814dc78dee>`_  2020-05-29   ``add separate example dags and system tests for GCSToGoogleSheetsOperator (#9066)``
`ada26be23c <https://github.com/apache/airflow/commit/ada26be23c913796c2ae77b91cb7d113dfec75a6>`_  2020-05-29   ``Add correct description for dst param in LocalFilesystemToGCSOperator (#9055)``
`81b2761b86 <https://github.com/apache/airflow/commit/81b2761b86dae2d21a6ee859d49c08d46fea6def>`_  2020-05-29   ``add example dag and system test for GoogleSheetsToGCSOperator (#9056)``
`0b0e4f7a4c <https://github.com/apache/airflow/commit/0b0e4f7a4cceff3efe15161fb40b984782760a34>`_  2020-05-26   ``Preparing for RC3 relase of backports (#9026)``
`00642a46d0 <https://github.com/apache/airflow/commit/00642a46d019870c4decb3d0e47c01d6a25cb88c>`_  2020-05-26   ``Fixed name of 20 remaining wrongly named operators. (#8994)``
`3994030ea6 <https://github.com/apache/airflow/commit/3994030ea678727daaf9c2bfed0ca94a096f8d2a>`_  2020-05-26   ``Refactor BigQuery operators (#8858)``
`cdb3f25456 <https://github.com/apache/airflow/commit/cdb3f25456e49d0199cd7ccd680626dac01c9be6>`_  2020-05-26   ``All classes in backport providers are now importable in Airflow 1.10 (#8991)``
`1d36b0303b <https://github.com/apache/airflow/commit/1d36b0303b8632fce6de78ca4e782ae26ee06fea>`_  2020-05-23   ``Fix references in docs (#8984)``
`cf5cf45e1c <https://github.com/apache/airflow/commit/cf5cf45e1c0dff9a40e02f0dc221542f974831a7>`_  2020-05-23   ``Support YAML input for CloudBuildCreateOperator (#8808)``
`499493c5c5 <https://github.com/apache/airflow/commit/499493c5c5cf324ab8452ead80a10b71ce0c3b14>`_  2020-05-19   ``[AIRFLOW-6586] Improvements to gcs sensor (#7197)``
`375d1ca229 <https://github.com/apache/airflow/commit/375d1ca229464617780623c61c6e8a1bf570c87f>`_  2020-05-19   ``Release candidate 2 for backport packages 2020.05.20 (#8898)``
`841d816647 <https://github.com/apache/airflow/commit/841d81664737c25d73d095a7dab5de80d369c87c>`_  2020-05-19   ``Allow setting the pooling time in DLPHook (#8824)``
`12c5e5d8ae <https://github.com/apache/airflow/commit/12c5e5d8ae25fa633efe63ccf4db389e2b796d79>`_  2020-05-17   ``Prepare release candidate for backport packages (#8891)``
`f3521fb0e3 <https://github.com/apache/airflow/commit/f3521fb0e36733d8bd356123e56a453fd37a6dca>`_  2020-05-16   ``Regenerate readme files for backport package release (#8886)``
`15273f0ea0 <https://github.com/apache/airflow/commit/15273f0ea05ec579c631ce26b5d620233ebdc4d2>`_  2020-05-16   ``Check for same task instead of Equality to detect Duplicate Tasks (#8828)``
`92585ca4cb <https://github.com/apache/airflow/commit/92585ca4cb375ac879f4ab331b3a063106eb7b92>`_  2020-05-15   ``Added automated release notes generation for backport operators (#8807)``
`e1e833bb26 <https://github.com/apache/airflow/commit/e1e833bb260879ecb9a1f80f28450a3656c0e598>`_  2020-05-13   ``Update GoogleBaseHook to not follow 308 and use 60s timeout (#8816)``
`8b54919711 <https://github.com/apache/airflow/commit/8b54919711a203c3f35d98c6310a55d4df5da590>`_  2020-05-12   ``Refactor BigQuery hook methods to use python library (#8631)``
`6911dfe837 <https://github.com/apache/airflow/commit/6911dfe8372a33df67ce1fdd3c2bca1047718f60>`_  2020-05-12   ``Fix template fields in Google operators (#8840)``
`4b06fde0f1 <https://github.com/apache/airflow/commit/4b06fde0f10ce178b3c336c5d901e3b089f2863d>`_  2020-05-12   ``Fix Flake8 errors (#8841)``
`1d12c347cb <https://github.com/apache/airflow/commit/1d12c347cb258e7081804da1f9f5ffdedc003163>`_  2020-05-12   ``Refactor BigQuery check operators (#8813)``
`493b685d78 <https://github.com/apache/airflow/commit/493b685d7879cfee532390ba0909d4b1d8764267>`_  2020-05-10   ``Add separate example DAGs and system tests for google cloud speech (#8778)``
`79ef8bed89 <https://github.com/apache/airflow/commit/79ef8bed891c22eb76adf99158288d1b44426dc0>`_  2020-05-10   ``Added Upload Multiple Entity Read Files to specified big query dataset (#8610)``
`280f1f0c4c <https://github.com/apache/airflow/commit/280f1f0c4cc49aba1b2f8b456326795733769d18>`_  2020-05-10   ``Correctly restore upstream_task_ids when deserializing Operators (#8775)``
`58aefb23b1 <https://github.com/apache/airflow/commit/58aefb23b1d456bbb24876a4e3ff14f25d6274b0>`_  2020-05-08   ``Added SDFtoGCSOperator (#8740)``
`723c52c942 <https://github.com/apache/airflow/commit/723c52c942b49b0e8c8fa8667a4a6a45fa249498>`_  2020-05-07   ``Add documentation for SpannerDeployInstanceOperator (#8750)``
`25ee4211b3 <https://github.com/apache/airflow/commit/25ee4211b345ce7c19fb7366fd230838c34f1d47>`_  2020-05-06   ``Support all RuntimeEnvironment parameters in DataflowTemplatedJobStartOperator (#8531)``
`8d6f1aa4b5 <https://github.com/apache/airflow/commit/8d6f1aa4b5bb8809ffc55dc0c62e6d0e89f331e5>`_  2020-05-05   ``Support num_retries field in env var for GCP connection (#8700)``
`67caae0f25 <https://github.com/apache/airflow/commit/67caae0f25db4eec42b8e81c85683aabdd8d6c1a>`_  2020-05-04   ``Add system test for gcs_to_bigquery (#8556)``
`bc45fa6759 <https://github.com/apache/airflow/commit/bc45fa6759203b4c26b52e693dac97486a84204e>`_  2020-05-03   ``Add system test and docs for Facebook Ads operators (#8503)``
`a28c66f23d <https://github.com/apache/airflow/commit/a28c66f23d373cd0f8bfc765a515f21d4b66a0e9>`_  2020-04-30   ``[AIRFLOW-4734] Upsert functionality for PostgresHook.insert_rows() (#8625)``
`992a24ce41 <https://github.com/apache/airflow/commit/992a24ce41067d3b73f293878e71835892cbb632>`_  2020-04-28   ``Split and improve BigQuery example DAG (#8529)``
`c1fb28230f <https://github.com/apache/airflow/commit/c1fb28230fa0d36ef86c452c70254b253a113f9c>`_  2020-04-28   ``Refactor BigQueryHook dataset operations (#8477)``
`e8d0f8feab <https://github.com/apache/airflow/commit/e8d0f8feab0ec08e248cd381359112ad6a832f5b>`_  2020-04-26   ``Improve idempodency in CloudDataTransferServiceCreateJobOperator (#8430)``
`37fdfa9775 <https://github.com/apache/airflow/commit/37fdfa9775f43a5fa15de9c53ab33ecdf97513c5>`_  2020-04-26   ``[AIRFLOW-6281] Create guide for GCS to GCS transfer operators (#8442)``
`14b22e6ffe <https://github.com/apache/airflow/commit/14b22e6ffeb3af1f68e8362a1d0061b41364019c>`_  2020-04-25   ``Add hook and operator for Google Cloud Life Sciences (#8481)``
`72ddc94d1e <https://github.com/apache/airflow/commit/72ddc94d1ee08b414102e0b8ac197a3d8e965707>`_  2020-04-23   ``Pass location using parmamter in Dataflow integration (#8382)``
`912aa4b423 <https://github.com/apache/airflow/commit/912aa4b4237695275db6379cf2f0a633ea6087bc>`_  2020-04-23   ``Added GoogleDisplayVideo360DownloadLineItemsOperator (#8174)``
`57c8c05839 <https://github.com/apache/airflow/commit/57c8c05839f66ed2909b1bee8ff6976432db82aa>`_  2020-04-22   ``Use python client in BQ hook create_empty_table/dataset and table_exists (#8377)``
`5d3a7eef30 <https://github.com/apache/airflow/commit/5d3a7eef30b30fa466d8173f13abe4c356d73aef>`_  2020-04-20   ``Allow multiple extra_packages in Dataflow (#8394)``
`79c99b1b6a <https://github.com/apache/airflow/commit/79c99b1b6ae2ff5b0c8ab892f7f3fb1b44724121>`_  2020-04-18   ``Added location parameter to BigQueryCheckOperator (#8273)``
`79d3f33c1b <https://github.com/apache/airflow/commit/79d3f33c1b65c9c7e7b1a75e25d38cab9aa4517f>`_  2020-04-17   ``Clean up temporary files in Dataflow operators (#8313)``
`efcffa323d <https://github.com/apache/airflow/commit/efcffa323ddb5aa9f5907aa86808f3f3b4f5bd87>`_  2020-04-16   ``Add Dataproc SparkR Example (#8240)``
`b198a1fa94 <https://github.com/apache/airflow/commit/b198a1fa94c44228dc7358552aeb6a5371ae0da2>`_  2020-04-15   ``Create guide for BigQuery operators (#8276)``
`2636cc932c <https://github.com/apache/airflow/commit/2636cc932c3b156644edd46635cf9ff995c83159>`_  2020-04-14   ``Raise exception when GCP credential doesn't support account impersonation (#8213)``
`eee4ebaeeb <https://github.com/apache/airflow/commit/eee4ebaeeb1991480ee178ddb600bc69b2a88764>`_  2020-04-14   ``Added Facebook Ads Operator #7887 (#8008)``
`8cae07ea18 <https://github.com/apache/airflow/commit/8cae07ea1873a90516120d9ffbd28e7fdd2f78a4>`_  2020-04-14   ``fixed typo (#8294)``
`45c8983306 <https://github.com/apache/airflow/commit/45c8983306ab1c54abdacd8f870e790fad25cb37>`_  2020-04-13   ``Less aggressive eager upgrade of requirements (#8267)``
`1fd9ed3840 <https://github.com/apache/airflow/commit/1fd9ed3840361afa1e9456ccb0dfd5a60fba4e85>`_  2020-04-13   ``Add mypy plugin for decorators. (#8145)``
`327b0a9f77 <https://github.com/apache/airflow/commit/327b0a9f77bbcbe3f977a37de04264c2eff4bee1>`_  2020-04-13   ``Added GoogleDisplayVideo360UploadLineItemsOperator (#8216)``
`bb5e403a32 <https://github.com/apache/airflow/commit/bb5e403a320e7377e5040cb180f61b4f5a9ea558>`_  2020-04-10   ``Honor schema type for MySQL to GCS data pre-process (#8090)``
`87969a350d <https://github.com/apache/airflow/commit/87969a350ddd41e9e77776af6d780b31e363eaca>`_  2020-04-09   ``[AIRFLOW-6515] Change Log Levels from Info/Warn to Error (#8170)``
`3fc89f29f5 <https://github.com/apache/airflow/commit/3fc89f29f5bcd1529089fa6cb9c44843614f9ec5>`_  2020-04-06   ``[AIRFLOW-7106] Cloud data fusion integration - Allow to pass args to start pipeline (#7849)``
`7ef75d2393 <https://github.com/apache/airflow/commit/7ef75d2393f30d155de550e6d1ee8c055e2abfee>`_  2020-04-03   ``[AIRFLOW-7117] Honor self.schema in sql_to_gcs as schema to upload (#8049)``
`ed2bc00576 <https://github.com/apache/airflow/commit/ed2bc00576b39a88e3e1fb79092494f4bfdcbf5c>`_  2020-04-02   ``Add Google Ads list accounts operator (#8007)``
`3808a6206e <https://github.com/apache/airflow/commit/3808a6206e70d4af84b39ea7078df54f02c1435e>`_  2020-04-01   ``Unify Google class/package names (#8033)``
`8a02402576 <https://github.com/apache/airflow/commit/8a02402576f83869d5134b4bddef5d73c15a8320>`_  2020-03-31   ``Rename CloudBaseHook to GoogleBaseHook and move it to google.common (#8011)``
`8e89780071 <https://github.com/apache/airflow/commit/8e897800716c8ccedd1c53f2d083cb295786aa50>`_  2020-03-31   ``Add more refactor steps for providers.google (#8010)``
`aae3b8fb27 <https://github.com/apache/airflow/commit/aae3b8fb27870cb3cfba5ed73e35e08d520ef014>`_  2020-03-31   ``Individual package READMEs (#8012)``
`779023968f <https://github.com/apache/airflow/commit/779023968f983c91701f687bc823dc338934cdad>`_  2020-03-30   ``[AIRFLOW-7075] Operators for storing information from GCS into GA (#7743)``
`49abce5217 <https://github.com/apache/airflow/commit/49abce52178c81954f8a25608f70ffe02fcf7b19>`_  2020-03-30   ``Improve system tests for Cloud Build (#8003)``
`0f19a930d1 <https://github.com/apache/airflow/commit/0f19a930d1a7dec2a96bab0de144829f83cc0626>`_  2020-03-29   ``Remove GKEStartPodOperator when backporting (#7908)``
`0e1c238b2f <https://github.com/apache/airflow/commit/0e1c238b2fff3a092c93368125bc8d82abc4b308>`_  2020-03-28   ``Get Airflow Variables from GCP Secrets Manager (#7946)``
`eb4af4f944 <https://github.com/apache/airflow/commit/eb4af4f944c77e67e167bbb6b0a2aaf075a95b50>`_  2020-03-28   ``Make BaseSecretsBackend.build_path generic (#7948)``
`01f99426fd <https://github.com/apache/airflow/commit/01f99426fddd2a24552f352edcb271fa78cf3b15>`_  2020-03-28   ``Add download/upload operators for GCS and Google Sheets (#7866)``
`892522f8e2 <https://github.com/apache/airflow/commit/892522f8e2aeedc1ad842a08aaea967b0cae077f>`_  2020-03-26   ``Change signature of GSheetsHook methods (#7853)``
`bfd425157a <https://github.com/apache/airflow/commit/bfd425157a746402b516f8fc9e48f4ddccd794ce>`_  2020-03-26   ``Improve idempotency in MLEngineHook.create_model (#7811)``
`f9c226343d <https://github.com/apache/airflow/commit/f9c226343d94a7732da280d1dd086bf1ba291c77>`_  2020-03-26   ``Fix CloudSecretsManagerBackend invalid connections_prefix (#7861)``
`e3920f12f4 <https://github.com/apache/airflow/commit/e3920f12f483b53950507c50f6ab6a4318072859>`_  2020-03-26   ``Improve setUp/tearDown in Cloud Firestore system test (#7862)``
`8ba8a7295a <https://github.com/apache/airflow/commit/8ba8a7295a31f6b44894bfcaea36fa93b8d8c0d0>`_  2020-03-26   ``Improve example DAGs for Cloud Memorystore (#7855)``
`f7d1a437c1 <https://github.com/apache/airflow/commit/f7d1a437c17461b5ab768b75d58f0cb026b2a818>`_  2020-03-26   ``Fix CloudMemorystoreCreateInstanceAndImportOperator operator (#7856)``
`beef6c230e <https://github.com/apache/airflow/commit/beef6c230e4ff266af7c16b639bfda659b2bf6c0>`_  2020-03-26   ``Improve authorization in GCP system tests (#7863)``
`5f165f3e42 <https://github.com/apache/airflow/commit/5f165f3e4231ebd420ce643211a93e1fecf4877e>`_  2020-03-26   ``[AIRFLOW-5801] Get GCP credentials from file instead of JSON blob (#7869)``
`686d7d50bd <https://github.com/apache/airflow/commit/686d7d50bd21622724d6818021355bc6885fd3de>`_  2020-03-25   ``Standardize SecretBackend class names (#7846)``
`1982c3fdca <https://github.com/apache/airflow/commit/1982c3fdca1f04cfc41fc5b5e285d8f01c6b76ab>`_  2020-03-24   ``Run Dataflow for ML Engine summary in venv (#7809)``
`eef87b9953 <https://github.com/apache/airflow/commit/eef87b9953347a65421f315a07dbef37ded9df66>`_  2020-03-23   ``[AIRFLOW-7105] Unify Secrets Backend method interfaces (#7830)``
`529db07b2e <https://github.com/apache/airflow/commit/529db07b2ee73d886e37e8b3415462c730187b15>`_  2020-03-23   ``Improve Google PubSub hook publish method (#7831)``
`4bde99f132 <https://github.com/apache/airflow/commit/4bde99f1323d72f6c84c1548079d5e98fc0a2a9a>`_  2020-03-23   ``Make airflow/providers pylint compatible (#7802)``
`a001489b59 <https://github.com/apache/airflow/commit/a001489b5928ebfc35f990a29d1c9c2ecb80bd61>`_  2020-03-23   ``Improve example DAG for ML Engine (#7810)``
`9e5a8e7f83 <https://github.com/apache/airflow/commit/9e5a8e7f83cf2368315fce62f8d81304f7ba2f04>`_  2020-03-23   ``Add call to Super class in 'google' providers (#7823)``
`b86bf79bff <https://github.com/apache/airflow/commit/b86bf79bff615e61de98bead4d02eace5690d5fb>`_  2020-03-23   ``Fix typo in GCP credentials_provider's docstring (#7818)``
`56c013ce92 <https://github.com/apache/airflow/commit/56c013ce922eb18e5f7dd4410986afbcc6f29025>`_  2020-03-23   ``Add missing docstring in BigQueryHook.create_empty_table (#7817)``
`426a79847c <https://github.com/apache/airflow/commit/426a79847ced832ca3f67c135fd8830ebf1de7d2>`_  2020-03-23   ``Imrove support for laatest API in  MLEngineStartTrainingJobOperator (#7812)``
`cdf1809fce <https://github.com/apache/airflow/commit/cdf1809fce0e59c8379a799f1738d8d813abbf51>`_  2020-03-23   ``[AIRFLOW-7104] Add Secret backend for GCP Secrets Manager (#7795)``
`27dac00e12 <https://github.com/apache/airflow/commit/27dac00e125b87626a0b87074d61e6d38031bf47>`_  2020-03-22   ``[AIRFLOW-7099] Improve system test for cloud transfer service (#7794)``
`0daf5d729a <https://github.com/apache/airflow/commit/0daf5d729acef4e9aef5226452dff774e80430cd>`_  2020-03-22   ``Add ability to specify a maximum modified time for objects in GCSToGCSOperator (#7791)``
`c8088c2bd7 <https://github.com/apache/airflow/commit/c8088c2bd70a16605a5d4b1a66a22309359d6712>`_  2020-03-20   ``[AIRFLOW-7100] Add GoogleAnalyticsGetAdsLinkOperator (#7781)``
`5106a29314 <https://github.com/apache/airflow/commit/5106a29314b413d168bcba7a64bf91c04fdb5dfe>`_  2020-03-20   ``[AIRFLOW-6752] Add GoogleAnalyticsRetrieveAdsLinksListOperator (#7748)``
`759ce2a80c <https://github.com/apache/airflow/commit/759ce2a80c95832fe4773c9f4fde23e1b03cbc6f>`_  2020-03-20   ``[AIRFLOW-6978] Add PubSubPullOperator (#7766)``
`6b9b214e4c <https://github.com/apache/airflow/commit/6b9b214e4c3b3afa8ea2e1a5c1e24993013d60ac>`_  2020-03-20   ``[AIRFLOW-6732] Add GoogleAdsHook and GoogleAdsToGcsOperator (#7692)``
`b118916969 <https://github.com/apache/airflow/commit/b11891696946d1461174b385c88d6af8abb99768>`_  2020-03-19   ``[AIRFLOW-7069] Fix cloudsql system tests (#7770)``
`ae854cae5a <https://github.com/apache/airflow/commit/ae854cae5a2cf8cae37edf7e0813ad01bccfbc30>`_  2020-03-19   ``[AIRFLOW-7082] Remove catch_http_exception decorator in GCP hooks (#7756)``
`7e1e954d23 <https://github.com/apache/airflow/commit/7e1e954d23ce272b0a71188f0f535e20d54be443>`_  2020-03-19   ``[AIRFLOW-7085] Cache credentials, project_id in GCP Base Hook (#7759)``
`6e21c139b3 <https://github.com/apache/airflow/commit/6e21c139b3cce3f895040939f0b02e3e0ba36141>`_  2020-03-19   ``[AIRFLOW-XXXX] Fix reference to GCP classes in guides (#7762)``
`ce022a3f72 <https://github.com/apache/airflow/commit/ce022a3f72b7735087d4c3bbe81d293a0ab75327>`_  2020-03-19   ``[AIRFLOW-XXXX] Add cross-references for operators guide (#7760)``
`029c84e552 <https://github.com/apache/airflow/commit/029c84e5527b6db6bdbdbe026f455da325bedef3>`_  2020-03-18   ``[AIRFLOW-5421] Add Presto to GCS transfer operator (#7718)``
`63a3102ede <https://github.com/apache/airflow/commit/63a3102ede8fb8f764d251b20cad5ee5bef84f50>`_  2020-03-18   ``[AIRFLOW-7064] Add CloudFirestoreExportDatabaseOperator (#7725)``
`73305c7bd5 <https://github.com/apache/airflow/commit/73305c7bd57f14444804c13b8b290f479832d3db>`_  2020-03-18   ``[AIRFLOW-7081] Remove env variables from GCP guide (#7755)``
`60fdbf6d92 <https://github.com/apache/airflow/commit/60fdbf6d9255d34a8967400e9585b1cd5d29d3e9>`_  2020-03-18   ``[AIRFLOW-5610] Add ability to specify multiple objects to copy in GCSToGCSOperator (#7728)``
`de7e934ca3 <https://github.com/apache/airflow/commit/de7e934ca3f21ce82f67accf92811b3ac044476f>`_  2020-03-17   ``[AIRFLOW-7079] Remove redundant code for storing template_fields (#7750)``
`0de0347b27 <https://github.com/apache/airflow/commit/0de0347b27a961c46ee49da6dfa9205321657749>`_  2020-03-17   ``[AIRFLOW-6855]: Escape project_dataset_table in SQL query in gcs to bq … (#7475)``
`91557c6f87 <https://github.com/apache/airflow/commit/91557c6f87529c010b8ad1110ece35fd7fd751e4>`_  2020-03-17   ``[AIRFLOW-7073] GKEStartPodOperator always use connection credentials (#7738)``
`51161dbd9d <https://github.com/apache/airflow/commit/51161dbd9de0c966016cec4d5036877890daee7c>`_  2020-03-16   ``[AIRFLOW-5664] Store timestamps with microseconds precision (#6354)``
`2bc020c431 <https://github.com/apache/airflow/commit/2bc020c43112dd3a769311de8d5012e8e8f399ee>`_  2020-03-14   ``[AIRFLOW-7055] Verbose logging option for google provider (#7711)``
`c997cab42d <https://github.com/apache/airflow/commit/c997cab42d8695ac444e63dfe4b948a7ea82ed89>`_  2020-03-13   ``[AIRFLOW-6724] Add Google Analytics 360 Accounts Retrieve Operator (#7630)``
`137896f326 <https://github.com/apache/airflow/commit/137896f326cd29b59902a887e4c4e58f940ff62b>`_  2020-03-12   ``[AIRFLOW-7034] Remove feature: Assigning Dag to task using Bitshift Op (#7685)``
`1f77f943d5 <https://github.com/apache/airflow/commit/1f77f943d5d85f66b6a988e8ef6506525eaf4732>`_  2020-03-10   ``[AIRFLOW-6980] Improve system tests and building providers package (#7615)``
`bf9b6b6d70 <https://github.com/apache/airflow/commit/bf9b6b6d70455352bbf807871c8eeb6324be7e54>`_  2020-03-09   ``[AIRFLOW-5013] Add GCP Data Catalog Hook and operators (#7664)``
`e5130dc9fe <https://github.com/apache/airflow/commit/e5130dc9fe89187e95071e678ea3b46600866762>`_  2020-03-09   ``[AIRFLOW-2911] Add job cancellation capability to Dataflow service (#7659)``
`faf0df4b94 <https://github.com/apache/airflow/commit/faf0df4b9460b7f037ee390addbd2c6effcae013>`_  2020-03-09   ``[AIRFLOW-XXXX] Fix upsert operator in BQ example DAG (#7666)``
`42eef38217 <https://github.com/apache/airflow/commit/42eef38217e709bc7a7f71bf0286e9e61293a43e>`_  2020-03-07   ``[AIRFLOW-6877] Add cross-provider dependencies as extras (#7506)``
`b5b9795f04 <https://github.com/apache/airflow/commit/b5b9795f0446bb484a91ee485f49ea456f1c26c4>`_  2020-03-07   ``[AIRFLOW-6973] Make GCSCreateBucketOperator idempotent (fix) (#7624)``
`6b65038fb4 <https://github.com/apache/airflow/commit/6b65038fb409ba1040e70305444816d8f5cfdc47>`_  2020-03-06   ``[AIRFLOW-6990] Improve system tests for Google Marketing Platform (#7631)``
`755fe52249 <https://github.com/apache/airflow/commit/755fe52249ba1cd965cf2f87fa7a428b8197a38a>`_  2020-03-05   ``[AIRFLOW-6915] Add AI Platform Console Link for MLEngineStartTrainingJobOperator (#7535)``
`cb2f339116 <https://github.com/apache/airflow/commit/cb2f339116cf2093da447748892fac68aecbb888>`_  2020-03-04   ``[AIRFLOW-6973] Make GCSCreateBucketOperator idempotent (#7609)``
`09fea3ce8e <https://github.com/apache/airflow/commit/09fea3ce8e4d7816281963bb8f2cb06f4de6db5c>`_  2020-03-04   ``[AIRFLOW-6977] Fix BigQuery DTS example DAG (#7612)``
`8230ccc48b <https://github.com/apache/airflow/commit/8230ccc48b157c89b2b893d42c6fe1523b83363a>`_  2020-03-04   ``[AIRFLOW-6926] Fix Google Tasks operators return types and idempotency (#7547)``
`0d1e3088aa <https://github.com/apache/airflow/commit/0d1e3088aa9f16eaeeb7b18eccec8f35c79a53df>`_  2020-03-04   ``[AIRFLOW-6970] Improve GCP Video Intelligence system tests (#7604)``
`ab6bb0012c <https://github.com/apache/airflow/commit/ab6bb0012c38740b76e864d42d299c5c7a9972a3>`_  2020-03-03   ``[AIRFLOW-6971] Fix return type in CloudSpeechToTextRecognizeSpeechOperator (#7607)``
`3db4ade3dc <https://github.com/apache/airflow/commit/3db4ade3dc9660c21c28187100a22008552f2bd3>`_  2020-02-29   ``[AIRFLOW-6924] Fix Google DLP operators return types (#7546)``
`008b4bab14 <https://github.com/apache/airflow/commit/008b4bab14222da068b737d6332db4963b994007>`_  2020-02-27   ``[AIRFLOW-6730] Use total_seconds instead of seconds (#7363)``
`bb552b2d9f <https://github.com/apache/airflow/commit/bb552b2d9fd595cc3eb1b3a2f637f29b814878d7>`_  2020-02-25   ``[AIRFLOW-6908] Lazy load AirflowException (#7528)``
`d1a34246ac <https://github.com/apache/airflow/commit/d1a34246ac593901f8599b102dc3d7efa4dd61e4>`_  2020-02-25   ``[AIRFLOW-6593] Add GCP Stackdriver Alerting Hooks and Operators (#7322)``
`3320e432a1 <https://github.com/apache/airflow/commit/3320e432a129476dbc1c55be3b3faa3326a635bc>`_  2020-02-24   ``[AIRFLOW-6817] Lazy-load 'airflow.DAG' to keep user-facing API untouched (#7517)``
`dcf8743521 <https://github.com/apache/airflow/commit/dcf87435219307d4e916a8abc2b819ad75e2b1cf>`_  2020-02-24   ``[AIRFLOW-6894] Prevent db query in example_dags (#7516)``
`4d03e33c11 <https://github.com/apache/airflow/commit/4d03e33c115018e30fa413c42b16212481ad25cc>`_  2020-02-22   ``[AIRFLOW-6817] remove imports from 'airflow/__init__.py', replaced implicit imports with explicit imports, added entry to 'UPDATING.MD' - squashed/rebased (#7456)``
`35b9616378 <https://github.com/apache/airflow/commit/35b9616378d1cfba7c2eb3c71e20acb6734b7c77>`_  2020-02-21   ``[AIRFLOW-4973] Add Cloud Data Fusion Pipeline integration (#7486)``
`aff3a361b4 <https://github.com/apache/airflow/commit/aff3a361b4092212c0757f9ce88fa2e40d25d1f4>`_  2020-02-20   ``[AIRFLOW-6558] Campaign Manager operators for conversions (#7420)``
`9cbd7de6d1 <https://github.com/apache/airflow/commit/9cbd7de6d115795aba8bfb8addb060bfdfbdf87b>`_  2020-02-18   ``[AIRFLOW-6792] Remove _operator/_hook/_sensor in providers package and add tests (#7412)``
`5b199cb86b <https://github.com/apache/airflow/commit/5b199cb86be5b1aefbd8620185033d6f635713c1>`_  2020-02-17   ``[AIRFLOW-XXXX] Typo in example_bigquery DAG (#7429)``
`2c9345a8e0 <https://github.com/apache/airflow/commit/2c9345a8e03d37a2676efa2f2ea7e8b7814c5345>`_  2020-02-17   ``[AIRFLOW-6759] Added MLEngine operator/hook to cancel MLEngine jobs (#7400)``
`946bdc23c0 <https://github.com/apache/airflow/commit/946bdc23c039637b0383e1269f99bdd1b2426565>`_  2020-02-16   ``[AIRFLOW-6405] Add GCP BigQuery Table Upsert Operator (#7126)``
`2381c820c8 <https://github.com/apache/airflow/commit/2381c820c8aaeffc1c9b4ed47832038833400eb8>`_  2020-02-13   ``[AIRFLOW-6505] Let emoji encoded properly for json.dumps() (#7399)``
`04c1fefbf2 <https://github.com/apache/airflow/commit/04c1fefbf26a73ed13881d2ec14eada48028ff72>`_  2020-02-03   ``[AIRFLOW-6676] added GCSDeleteBucketOperator (#7307)``
`a0252748ff <https://github.com/apache/airflow/commit/a0252748ff312daede15c6f0a3d39e16c774461c>`_  2020-02-03   ``[AIRFLOW-6717] Remove non-existent field from templated_fields (#7340)``
`97a429f9d0 <https://github.com/apache/airflow/commit/97a429f9d0cf740c5698060ad55f11e93cb57b55>`_  2020-02-02   ``[AIRFLOW-6714] Remove magic comments about UTF-8 (#7338)``
`9d8d075578 <https://github.com/apache/airflow/commit/9d8d0755789d4aeadc5d3015f3cdde62901f85b8>`_  2020-02-03   ``[AIRFLOW-6715] Fix Google Cloud DLP Example DAG (#7337)``
`cf141506a2 <https://github.com/apache/airflow/commit/cf141506a25dbba279b85500d781f7e056540721>`_  2020-02-02   ``[AIRFLOW-6708] Set unique logger names (#7330)``
`373c6aa4a2 <https://github.com/apache/airflow/commit/373c6aa4a208284b5ff72987e4bd8f4e2ada1a1b>`_  2020-01-30   ``[AIRFLOW-6682] Move GCP classes to providers package (#7295)``
`83c037873f <https://github.com/apache/airflow/commit/83c037873ff694eed67ba8b30f2d9c88b2c7c6f2>`_  2020-01-30   ``[AIRFLOW-6674] Move example_dags in accordance with AIP-21 (#7287)``
`057f3ae3a4 <https://github.com/apache/airflow/commit/057f3ae3a4afedf6d462ecf58b01dd6304d3e135>`_  2020-01-29   ``[AIRFLOW-6670][depends on AIRFLOW-6669] Move contrib operators to providers package (#7286)``
`ceea293c16 <https://github.com/apache/airflow/commit/ceea293c1652240e7e856c201e4341a87ef97a0f>`_  2020-01-28   ``[AIRFLOW-6656] Fix AIP-21 moving (#7272)``
`c42a375e79 <https://github.com/apache/airflow/commit/c42a375e799e5adb3f9536616372dc90ff47e6c8>`_  2020-01-27   ``[AIRFLOW-6644][AIP-21] Move service classes to providers package (#7265)``
`059eda05f8 <https://github.com/apache/airflow/commit/059eda05f82fefce4410f44f761f945a27d83daf>`_  2020-01-21   ``[AIRFLOW-6610] Move software classes to providers package (#7231)``
`f4d3e5e545 <https://github.com/apache/airflow/commit/f4d3e5e54507f52a00a9b95aa48eb0260e17224d>`_  2020-01-13   ``[AIRFLOW-6102] [AIP-21] Rename Dataproc operators (#7151)``
`e7bf8ecb48 <https://github.com/apache/airflow/commit/e7bf8ecb48f0299af8091433535ac573c2afd1cf>`_  2020-01-13   ``[AIRFLOW-6119] [AIP-21] Rename GCS operators, hooks and sensors (#7125)``
`5b6772cb83 <https://github.com/apache/airflow/commit/5b6772cb8391b248cb4b7be5fd3d5c035280fac1>`_  2020-01-09   ``[AIRFLOW-6125] [AIP-21] Rename S3 operator and SFTP operator (#7112)``
`4f8592ae8f <https://github.com/apache/airflow/commit/4f8592ae8f52ab7f42623d3b43eef0928c9aafb2>`_  2020-01-08   ``[AIRFLOW-6118] [AIP-21] Rename Pubsub operators and hook (#7046)``
`20299473f1 <https://github.com/apache/airflow/commit/20299473f11add6531f607256ee8a0f7f9507ab8>`_  2020-01-03   ``[AIRFLOW-6115] [AIP-21] Rename GCP vision operators (#7020)``
`18e8cea4e7 <https://github.com/apache/airflow/commit/18e8cea4e7487a7dfefc03661e5ebe54c4104ead>`_  2020-01-03   ``[AIRFLOW-6428] Fix import path for airflow.utils.dates.days_ago in Example DAGs (#7007)``
`95087af140 <https://github.com/apache/airflow/commit/95087af14091f28a83ced8ff1860b86dfd93f93d>`_  2019-12-31   ``[AIRFLOW-6110] [AIP-21] Rename natural_language service (#6968)``
`69629a5a94 <https://github.com/apache/airflow/commit/69629a5a948ab2c4ac04a4a4dca6ac86d19c11bd>`_  2019-12-09   ``[AIRFLOW-5807] Move SFTP from contrib to providers. (#6464)``
`25e9047a4a <https://github.com/apache/airflow/commit/25e9047a4a4da5fad4f85c366e3a6262c0a4f68e>`_  2019-12-09   ``[AIRFLOW-6193] Do not use asserts in Airflow main code (#6749)``
`ed0a14f321 <https://github.com/apache/airflow/commit/ed0a14f321b9dab3554ae395c11c147258536ce8>`_  2019-12-09   ``[AIRFLOW-6120] Rename GoogleCloudBaseHook (#6734)``
`2f2f89c148 <https://github.com/apache/airflow/commit/2f2f89c148e2b694aee9402707f68065ee7320f8>`_  2019-12-01   ``[AIRFLOW-6139] Consistent spaces in pylint enable/disable (#6701)``
`03c870a617 <https://github.com/apache/airflow/commit/03c870a6172ab232af6319a30ad8d46622359b10>`_  2019-11-26   ``[AIRFLOW-6010] Remove cyclic imports and pylint hacks (#6601)``
`5c4cfea8c0 <https://github.com/apache/airflow/commit/5c4cfea8c0f488496c1cbcc4c6c5db13d8210979>`_  2019-11-15   ``[AIRFLOW-5718] Add SFTPToGoogleCloudStorageOperator (#6393)``
`44a8c37a9a <https://github.com/apache/airflow/commit/44a8c37a9a8668469aa825ad21057cca6ac2c186>`_  2019-11-13   ``[AIRFLOW-XXX] Fix the docstring for Dataproc get_job method (#6581)``
`d633d3ac44 <https://github.com/apache/airflow/commit/d633d3ac44c395e6c43cd388f98fba1ce1c435a3>`_  2019-11-13   ``[AIRFLOW-5691] Rewrite Dataproc operators to use python library (#6371)``
`d985c02d9f <https://github.com/apache/airflow/commit/d985c02d9fa3d9ec946abc1735b0551fd61fb9f0>`_  2019-11-05   ``[AIRFLOW-XXX] Add How-To-Guide to GCP PubSub (#6497)``
`a296cdabdb <https://github.com/apache/airflow/commit/a296cdabdb9c9c65cf9a48329cb776aed5c82d43>`_  2019-11-04   ``[AIRFLOW-5743] Move Google PubSub to providers package (#6476)``
`470b2a779d <https://github.com/apache/airflow/commit/470b2a779d031406a3d5925f2fa2ec40e5c3bccb>`_  2019-10-30   ``[AIRFLOW-5741] Move Cloud Natural Language to providers (#6421)``
`f2caa451fc <https://github.com/apache/airflow/commit/f2caa451fc2b8ee59163314f9ec1cc372acbadf1>`_  2019-10-27   ``[AIRFLOW-5742] Move Google Cloud Vision to providers package (#6424)``
`16d7accb22 <https://github.com/apache/airflow/commit/16d7accb22c866d4fbf368e4d979dc1c4a41d93c>`_  2019-10-22   ``[AIRFLOW-4971] Add Google Display & Video 360 integration (#6170)``
`4e661f535d <https://github.com/apache/airflow/commit/4e661f535dea613f9b2e0075676f9a73a97461fe>`_  2019-10-22   ``[AIRFLOW-5379] Add Google Search Ads 360 operators (#6228)``
`19e32b4e2c <https://github.com/apache/airflow/commit/19e32b4e2c798f662e5d8d1e7c65036c5e7ac125>`_  2019-10-18   ``[AIRFLOW-5656] Rename provider to providers module (#6333)``
=================================================================================================  ===========  ======================================================================================================================================================================
