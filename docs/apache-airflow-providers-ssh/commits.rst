
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


Package apache-airflow-providers-ssh
------------------------------------------------------

`Secure Shell (SSH) <https://tools.ietf.org/html/rfc4251>`__


This is detailed commit list of changes for versions provider package: ``ssh``.
For high-level changelog, see :doc:`package information including changelog <index>`.



3.7.0
.....

Latest change: 2023-05-03

=================================================================================================  ===========  ======================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ======================================================================
`0a30706aa7 <https://github.com/apache/airflow/commit/0a30706aa7c581905ca99a8b6e2f05960d480729>`_  2023-05-03   ``Use 'AirflowProviderDeprecationWarning' in providers (#30975)``
`eef5bc7f16 <https://github.com/apache/airflow/commit/eef5bc7f166dc357fea0cc592d39714b1a5e3c14>`_  2023-05-03   ``Add full automation for min Airflow version for providers (#30994)``
`a7eb32a5b2 <https://github.com/apache/airflow/commit/a7eb32a5b222e236454d3e474eec478ded7c368d>`_  2023-04-30   ``Bump minimum Airflow version in providers (#30917)``
`d23a3bbed8 <https://github.com/apache/airflow/commit/d23a3bbed89ae04369983f21455bf85ccc1ae1cb>`_  2023-04-04   ``Add mechanism to suspend providers (#30422)``
=================================================================================================  ===========  ======================================================================

3.6.0
.....

Latest change: 2023-04-02

=================================================================================================  ===========  ==========================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==========================================================================
`55dbf1ff1f <https://github.com/apache/airflow/commit/55dbf1ff1fb0b22714f695a66f6108b3249d1199>`_  2023-04-02   ``Prepare docs for April 2023 wave of Providers (#30378)``
`fe727f985b <https://github.com/apache/airflow/commit/fe727f985b1053b838433b817458517c0c0f2480>`_  2023-03-21   ``SSHOperator - Restore ability to override SSHHook cmd_timeout (#30190)``
=================================================================================================  ===========  ==========================================================================

3.5.0
.....

Latest change: 2023-03-03

=================================================================================================  ===========  ==================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==================================================================
`fcd3c0149f <https://github.com/apache/airflow/commit/fcd3c0149f17b364dfb94c0523d23e3145976bbe>`_  2023-03-03   ``Prepare docs for 03/2023 wave of Providers (#29878)``
`fd000684d0 <https://github.com/apache/airflow/commit/fd000684d05a993ade3fef38b683ef3cdfdfc2b6>`_  2023-02-19   ``SSH Provider: Add cmd_timeout to ssh connection extra (#29347)``
=================================================================================================  ===========  ==================================================================

3.4.0
.....

Latest change: 2023-01-02

=================================================================================================  ===========  =======================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =======================================================================
`5246c009c5 <https://github.com/apache/airflow/commit/5246c009c557b4f6bdf1cd62bf9b89a2da63f630>`_  2023-01-02   ``Prepare docs for Jan 2023 wave of Providers (#28651)``
`4f006e8c71 <https://github.com/apache/airflow/commit/4f006e8c71f850fce0450fbabd6aa6d61487498e>`_  2022-12-28   ``Add .bash and other extensions to SSHOperator template_ext (#28617)``
`38e40c6dc4 <https://github.com/apache/airflow/commit/38e40c6dc45b92b274a06eafd8790140a0c3c7b8>`_  2022-12-21   ``Remove outdated compat imports/code from providers (#28507)``
`b5338b5825 <https://github.com/apache/airflow/commit/b5338b5825859355b017bed3586d5a42208f1391>`_  2022-12-07   ``Add test_connection method for SSHHook (#28184)``
`2b107e6f50 <https://github.com/apache/airflow/commit/2b107e6f504732715702ea65e77986c2d42f5d61>`_  2022-12-04   ``SSH task exit code added to XCOM as 'ssh_exit' key (#27370)``
`4a3a429658 <https://github.com/apache/airflow/commit/4a3a42965801823c39baaccfa96c5e4cffae4012>`_  2022-12-03   ``[misc] Get rid of 'pass' statement in conditions (#27775)``
=================================================================================================  ===========  =======================================================================

3.3.0
.....

Latest change: 2022-11-15

=================================================================================================  ===========  =========================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =========================================================================
`12c3c39d1a <https://github.com/apache/airflow/commit/12c3c39d1a816c99c626fe4c650e88cf7b1cc1bc>`_  2022-11-15   ``pRepare docs for November 2022 wave of Providers (#27613)``
`8f152a102b <https://github.com/apache/airflow/commit/8f152a102baf6851a719e4ad10fbb15e928fa72b>`_  2022-11-08   ``Apply log formatter on every ouput line in SSHOperator (#27442)``
`dc760b45ea <https://github.com/apache/airflow/commit/dc760b45eaeccc3ff35a5acdfe70968ca0451331>`_  2022-11-07   ``SSHOperator ignores cmd_timeout (#27182) (#27184)``
`9ab1a6a3e7 <https://github.com/apache/airflow/commit/9ab1a6a3e70b32a3cddddf0adede5d2f3f7e29ea>`_  2022-10-27   ``Update old style typing (#26872)``
`13b6b3b078 <https://github.com/apache/airflow/commit/13b6b3b0780036ff47a92757d960468f628aa578>`_  2022-10-26   ``Added docs regarding templated field (#27301)``
`a8a67a3f40 <https://github.com/apache/airflow/commit/a8a67a3f40cdb206676a167829b61a4207ae1fe9>`_  2022-10-26   ``Added environment to templated SSHOperator fields (#26824)``
`78b8ea2f22 <https://github.com/apache/airflow/commit/78b8ea2f22239db3ef9976301234a66e50b47a94>`_  2022-10-24   ``Move min airflow version to 2.3.0 for all providers (#27196)``
`2a34dc9e84 <https://github.com/apache/airflow/commit/2a34dc9e8470285b0ed2db71109ef4265e29688b>`_  2022-10-23   ``Enable string normalization in python formatting - providers (#27205)``
`674f9ce6ea <https://github.com/apache/airflow/commit/674f9ce6eaae533cfe31bc92cc92fa75ed7223fc>`_  2022-10-01   ``A few docs fixups (#26788)``
=================================================================================================  ===========  =========================================================================

3.2.0
.....

Latest change: 2022-09-28

=================================================================================================  ===========  ====================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ====================================================================================
`f8db64c35c <https://github.com/apache/airflow/commit/f8db64c35c8589840591021a48901577cff39c07>`_  2022-09-28   ``Update docs for September Provider's release (#26731)``
`06acf40a43 <https://github.com/apache/airflow/commit/06acf40a4337759797f666d5bb27a5a393b74fed>`_  2022-09-13   ``Apply PEP-563 (Postponed Evaluation of Annotations) to non-core airflow (#26289)``
`2f26da7023 <https://github.com/apache/airflow/commit/2f26da70230d7d1cf7dfb3a20d38e9a5844862a7>`_  2022-08-27   ``feat: load host keys to save new host key (#25979)``
=================================================================================================  ===========  ====================================================================================

3.1.0
.....

Latest change: 2022-07-13

=================================================================================================  ===========  =============================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =============================================================================
`d2459a241b <https://github.com/apache/airflow/commit/d2459a241b54d596ebdb9d81637400279fff4f2d>`_  2022-07-13   ``Add documentation for July 2022 Provider's release (#25030)``
`ca99c23cb4 <https://github.com/apache/airflow/commit/ca99c23cb4741eda43ac910a7ad8eda3cfa6add8>`_  2022-07-13   ``Less verbose logging in ssh operator (#24915)``
`0de31bd73a <https://github.com/apache/airflow/commit/0de31bd73a8f41dded2907f0dee59dfa6c1ed7a1>`_  2022-06-29   ``Move provider dependencies to inside provider folders (#24672)``
`510a6bab45 <https://github.com/apache/airflow/commit/510a6bab4595cce8bd5b1447db957309d70f35d9>`_  2022-06-28   ``Remove 'hook-class-names' from provider.yaml (#24702)``
`9c59831ee7 <https://github.com/apache/airflow/commit/9c59831ee78f14de96421c74986933c494407afa>`_  2022-06-21   ``Update providers to use functools compat for ''cached_property'' (#24582)``
`f3aacebe50 <https://github.com/apache/airflow/commit/f3aacebe502c4ea5dc2b7d29373539296fa037eb>`_  2022-06-20   ``Convert sftp hook to use paramiko instead of pysftp (#24512)``
=================================================================================================  ===========  =============================================================================

3.0.0
.....

Latest change: 2022-06-09

=================================================================================================  ===========  ==================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==================================================================================
`dcdcf3a2b8 <https://github.com/apache/airflow/commit/dcdcf3a2b8054fa727efb4cd79d38d2c9c7e1bd5>`_  2022-06-09   ``Update release notes for RC2 release of Providers for May 2022 (#24307)``
`717a7588bc <https://github.com/apache/airflow/commit/717a7588bc8170363fea5cb75f17efcf68689619>`_  2022-06-07   ``Update package description to remove double min-airflow specification (#24292)``
`aeabe994b3 <https://github.com/apache/airflow/commit/aeabe994b3381d082f75678a159ddbb3cbf6f4d3>`_  2022-06-07   ``Prepare docs for May 2022 provider's release (#24231)``
`027b707d21 <https://github.com/apache/airflow/commit/027b707d215a9ff1151717439790effd44bab508>`_  2022-06-05   ``Add explanatory note for contributors about updating Changelog (#24229)``
`fb1187dbec <https://github.com/apache/airflow/commit/fb1187dbec19377d2a8b7dbc35813b2aaa56506f>`_  2022-06-03   ``Add disabled_algorithms as an extra parameter for SSH connections (#24090)``
`ddb2a4f47b <https://github.com/apache/airflow/commit/ddb2a4f47b9aec14e1b16498f6c0a372a3f8b6c3>`_  2022-06-02   ``fixing SSHHook bug when using allow_host_key_change param (#24116)``
=================================================================================================  ===========  ==================================================================================

2.4.4
.....

Latest change: 2022-05-12

=================================================================================================  ===========  ============================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ============================================================
`75c60923e0 <https://github.com/apache/airflow/commit/75c60923e01375ffc5f71c4f2f7968f489e2ca2f>`_  2022-05-12   ``Prepare provider documentation 2022.05.11 (#23631)``
`e63dbdc431 <https://github.com/apache/airflow/commit/e63dbdc431c2fa973e9a4c0b48ec6230731c38d1>`_  2022-05-10   ``Add exception to catch single line private keys (#23043)``
=================================================================================================  ===========  ============================================================

2.4.3
.....

Latest change: 2022-03-22

=================================================================================================  ===========  ==============================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==============================================================
`d7dbfb7e26 <https://github.com/apache/airflow/commit/d7dbfb7e26a50130d3550e781dc71a5fbcaeb3d2>`_  2022-03-22   ``Add documentation for bugfix release of Providers (#22383)``
=================================================================================================  ===========  ==============================================================

2.4.2
.....

Latest change: 2022-03-14

=================================================================================================  ===========  ====================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ====================================================================
`16adc035b1 <https://github.com/apache/airflow/commit/16adc035b1ecdf533f44fbb3e32bea972127bb71>`_  2022-03-14   ``Add documentation for Classifier release for March 2022 (#22226)``
=================================================================================================  ===========  ====================================================================

2.4.1
.....

Latest change: 2022-03-07

=================================================================================================  ===========  ========================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ========================================================
`f5b96315fe <https://github.com/apache/airflow/commit/f5b96315fe65b99c0e2542831ff73a3406c4232d>`_  2022-03-07   ``Add documentation for Feb Providers release (#22056)``
=================================================================================================  ===========  ========================================================

2.4.0
.....

Latest change: 2022-02-08

=================================================================================================  ===========  ==========================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==========================================================================
`d94fa37830 <https://github.com/apache/airflow/commit/d94fa378305957358b910cfb1fe7cb14bc793804>`_  2022-02-08   ``Fixed changelog for January 2022 (delayed) provider's release (#21439)``
`6c3a67d4fc <https://github.com/apache/airflow/commit/6c3a67d4fccafe4ab6cd9ec8c7bacf2677f17038>`_  2022-02-05   ``Add documentation for January 2021 providers release (#21257)``
`ab762a5a8a <https://github.com/apache/airflow/commit/ab762a5a8ae147ae33500ee3c7e7a73d25d03ad7>`_  2022-02-04   ``Refactor SSH tests to not use SSH server in operator tests (#21326)``
`d353f023ff <https://github.com/apache/airflow/commit/d353f023ff8856c00b9f054526cb2e40ff0116ae>`_  2022-02-02   ``Add banner_timeout feature to SSH Hook/Operator (#21262)``
`b6edc3bfa1 <https://github.com/apache/airflow/commit/b6edc3bfa1ed46bed2ae23bb2baeefde3f9a59d3>`_  2022-02-01   ``Add a retry with wait interval for SSH operator #14489 (#19981)``
`cb73053211 <https://github.com/apache/airflow/commit/cb73053211367e2c2dd76d5279cdc7dc7b190124>`_  2022-01-27   ``Add optional features in providers. (#21074)``
`9ed9b5170c <https://github.com/apache/airflow/commit/9ed9b5170c8dbb11469a88c41e323d8b61a1e7e6>`_  2022-01-24   ``Fix last remaining MyPy errors (#21020)``
`602abe8394 <https://github.com/apache/airflow/commit/602abe8394fafe7de54df7e73af56de848cdf617>`_  2022-01-20   ``Remove ':type' lines now sphinx-autoapi supports typehints (#20951)``
`129b4d2ac2 <https://github.com/apache/airflow/commit/129b4d2ac2ce09d42fb487f8a9aaac7eb7901a05>`_  2022-01-09   ``Delay the creation of ssh proxy until get_conn() (#20474) (#20474)``
`f77417eb0d <https://github.com/apache/airflow/commit/f77417eb0d3f12e4849d80645325c02a48829278>`_  2021-12-31   ``Fix K8S changelog to be PyPI-compatible (#20614)``
`97496ba2b4 <https://github.com/apache/airflow/commit/97496ba2b41063fa24393c58c5c648a0cdb5a7f8>`_  2021-12-31   ``Update documentation for provider December 2021 release (#20523)``
`83f8e178ba <https://github.com/apache/airflow/commit/83f8e178ba7a3d4ca012c831a5bfc2cade9e812d>`_  2021-12-31   ``Even more typing in operators (template_fields/ext) (#20608)``
`d56e7b56bb <https://github.com/apache/airflow/commit/d56e7b56bb9827daaf8890557147fd10bdf72a7e>`_  2021-12-30   ``Fix template_fields type to have MyPy friendly Sequence type (#20571)``
`da783f88a1 <https://github.com/apache/airflow/commit/da783f88a16e20211d7087bd5c8802dc002c78a8>`_  2021-12-13   ``Fix MyPy Errors for SSH provider (#20241)``
=================================================================================================  ===========  ==========================================================================

2.3.0
.....

Latest change: 2021-10-29

=================================================================================================  ===========  ========================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ========================================================================================
`d9567eb106 <https://github.com/apache/airflow/commit/d9567eb106929b21329c01171fd398fbef2dc6c6>`_  2021-10-29   ``Prepare documentation for October Provider's release (#19321)``
`2197e4b59a <https://github.com/apache/airflow/commit/2197e4b59a7cf859eff5969b5f27b5e4f1084d3b>`_  2021-10-29   ``Correctly handle get_pty attribute if command passed as XComArg or template (#19323)``
`1571f80546 <https://github.com/apache/airflow/commit/1571f80546853688778c2a3ec5194e5c8be0edbd>`_  2021-10-14   ``Add pre-commit hook for common misspelling check in files (#18964)``
`73fcbb0e4e <https://github.com/apache/airflow/commit/73fcbb0e4e151c9965fd69ba08de59462bbbe6dc>`_  2021-10-13   ``Refactor SSHOperator so a subclass can run many commands (#10874) (#17378)``
`537963f24d <https://github.com/apache/airflow/commit/537963f24d83b08c546112bac33bf0f44d95fe1c>`_  2021-10-05   ``update minimum version of sshtunnel to 0.3.2 (#18684)``
=================================================================================================  ===========  ========================================================================================

2.2.0
.....

Latest change: 2021-09-30

=================================================================================================  ===========  ======================================================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ======================================================================================================================
`840ea3efb9 <https://github.com/apache/airflow/commit/840ea3efb9533837e9f36b75fa527a0fbafeb23a>`_  2021-09-30   ``Update documentation for September providers release (#18613)``
`68d99bc558 <https://github.com/apache/airflow/commit/68d99bc5582b52106f876ccc22cc1e115a42b252>`_  2021-09-10   ``[Airflow 16364] Add conn_timeout and cmd_timeout params to SSHOperator; add conn_timeout param to SSHHook (#17236)``
=================================================================================================  ===========  ======================================================================================================================

2.1.1
.....

Latest change: 2021-08-30

=================================================================================================  ===========  ============================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ============================================================================
`0a68588479 <https://github.com/apache/airflow/commit/0a68588479e34cf175d744ea77b283d9d78ea71a>`_  2021-08-30   ``Add August 2021 Provider's documentation (#17890)``
`be75dcd39c <https://github.com/apache/airflow/commit/be75dcd39cd10264048c86e74110365bd5daf8b7>`_  2021-08-23   ``Update description about the new ''connection-types'' provider meta-data``
`76ed2a49c6 <https://github.com/apache/airflow/commit/76ed2a49c6cd285bf59706cf04f39a7444c382c9>`_  2021-08-19   ``Import Hooks lazily individually in providers manager (#17682)``
`f42478009a <https://github.com/apache/airflow/commit/f42478009a9524fdc3d44eabb305f2e4930c166e>`_  2021-08-10   ``Ignores exception raised during closing SSH connection (#17528)``
=================================================================================================  ===========  ============================================================================

2.1.0
.....

Latest change: 2021-07-26

=================================================================================================  ===========  =========================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =========================================================================================
`87f408b1e7 <https://github.com/apache/airflow/commit/87f408b1e78968580c760acb275ae5bb042161db>`_  2021-07-26   ``Prepares docs for Rc2 release of July providers (#17116)``
`d02ded65ea <https://github.com/apache/airflow/commit/d02ded65eaa7d2281e249b3fa028605d1b4c52fb>`_  2021-07-15   ``Fixed wrongly escaped characters in amazon's changelog (#17020)``
`b916b75079 <https://github.com/apache/airflow/commit/b916b7507921129dc48d6add1bdc4b923b60c9b9>`_  2021-07-15   ``Prepare documentation for July release of providers. (#17015)``
`a2dc01b345 <https://github.com/apache/airflow/commit/a2dc01b34590fc7830bdb76fea653e1a0ebecbd3>`_  2021-07-03   ``SSHHook: Using correct hostname for host_key when using non-default ssh port (#15964)``
`7777d4f2fd <https://github.com/apache/airflow/commit/7777d4f2fd0a63758c34769f8aa0438c8b4c6d83>`_  2021-07-01   ``Correctly load openssh-gerenated private keys in SSHHook (#16756)``
`866a601b76 <https://github.com/apache/airflow/commit/866a601b76e219b3c043e1dbbc8fb22300866351>`_  2021-06-28   ``Removes pylint from our toolchain (#16682)``
`50e334df32 <https://github.com/apache/airflow/commit/50e334df3245072f55ce75c2611dca2df0cbd031>`_  2021-06-24   ``Add support for non-RSA type key for SFTP hook (#16314)``
=================================================================================================  ===========  =========================================================================================

2.0.0
.....

Latest change: 2021-06-18

=================================================================================================  ===========  ======================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ======================================================================
`bbc627a3da <https://github.com/apache/airflow/commit/bbc627a3dab17ba4cf920dd1a26dbed6f5cebfd1>`_  2021-06-18   ``Prepares documentation for rc2 release of Providers (#16501)``
`cbf8001d76 <https://github.com/apache/airflow/commit/cbf8001d7630530773f623a786f9eb319783b33c>`_  2021-06-16   ``Synchronizes updated changelog after buggfix release (#16464)``
`1fba5402bb <https://github.com/apache/airflow/commit/1fba5402bb14b3ffa6429fdc683121935f88472f>`_  2021-06-15   ``More documentation update for June providers release (#16405)``
`9c94b72d44 <https://github.com/apache/airflow/commit/9c94b72d440b18a9e42123d20d48b951712038f9>`_  2021-06-07   ``Updated documentation for June 2021 provider release (#16294)``
`37681bca00 <https://github.com/apache/airflow/commit/37681bca0081dd228ac4047c17631867bba7a66f>`_  2021-05-07   ``Auto-apply apply_default decorator (#15667)``
`807ad32ce5 <https://github.com/apache/airflow/commit/807ad32ce59e001cb3532d98a05fa7d0d7fabb95>`_  2021-05-01   ``Prepares provider release after PIP 21 compatibility (#15576)``
`7a0d412245 <https://github.com/apache/airflow/commit/7a0d4122459289e0f2db78ad2849d5ba42df4468>`_  2021-04-25   ``Add Connection Documentation to more Providers (#15408)``
`3e9e954d9e <https://github.com/apache/airflow/commit/3e9e954d9ec5236cbbc6da2091b38e69c1b4c0c0>`_  2021-04-07   ``Display explicit error in case UID has no actual username (#15212)``
=================================================================================================  ===========  ======================================================================

1.3.0
.....

Latest change: 2021-04-06

=================================================================================================  ===========  =============================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  =============================================================================
`042be2e4e0 <https://github.com/apache/airflow/commit/042be2e4e06b988f5ba2dc146f53774dabc8b76b>`_  2021-04-06   ``Updated documentation for provider packages before April release (#15236)``
`9b76b94c94 <https://github.com/apache/airflow/commit/9b76b94c940d472290861930a1d5860b43b3b2b2>`_  2021-04-02   ``A bunch of template_fields_renderers additions (#15130)``
`68e4c4dcb0 <https://github.com/apache/airflow/commit/68e4c4dcb0416eb51a7011a3bb040f1e23d7bba8>`_  2021-03-20   ``Remove Backport Providers (#14886)``
=================================================================================================  ===========  =============================================================================

1.2.0
.....

Latest change: 2021-02-27

=================================================================================================  ===========  ==============================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==============================================================================
`589d6dec92 <https://github.com/apache/airflow/commit/589d6dec922565897785bcbc5ac6bb3b973d7f5d>`_  2021-02-27   ``Prepare to release the next wave of providers: (#14487)``
`f180fa13bf <https://github.com/apache/airflow/commit/f180fa13bf2a0ffa31b30bb21468510fe8a20131>`_  2021-02-08   ``Added support for DSS, ECDSA, and Ed25519 private keys in SSHHook (#12467)``
`10343ec29f <https://github.com/apache/airflow/commit/10343ec29f8f0abc5b932ba26faf49bc63c6bcda>`_  2021-02-05   ``Corrections in docs and tools after releasing provider RCs (#14082)``
=================================================================================================  ===========  ==============================================================================

1.1.0
.....

Latest change: 2021-02-04

=================================================================================================  ===========  ================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ================================================================================
`88bdcfa0df <https://github.com/apache/airflow/commit/88bdcfa0df5bcb4c489486e05826544b428c8f43>`_  2021-02-04   ``Prepare to release a new wave of providers. (#14013)``
`ac2f72c98d <https://github.com/apache/airflow/commit/ac2f72c98dc0821b33721054588adbf2bb53bb0b>`_  2021-02-01   ``Implement provider versioning tools (#13767)``
`daedc99851 <https://github.com/apache/airflow/commit/daedc998519f534f604fdecb86b101fa4eb5b5dd>`_  2021-01-30   ``Fix decode error for ssh log (#13943)``
`a9ac2b040b <https://github.com/apache/airflow/commit/a9ac2b040b64de1aa5d9c2b9def33334e36a8d22>`_  2021-01-23   ``Switch to f-strings using flynt. (#13732)``
`3fd5ef3555 <https://github.com/apache/airflow/commit/3fd5ef355556cf0ad7896bb570bbe4b2eabbf46e>`_  2021-01-21   ``Add missing logos for integrations (#13717)``
`52339a55c0 <https://github.com/apache/airflow/commit/52339a55c054bddd1d46253575274a3d5d141ebe>`_  2021-01-08   ``[AIRFLOW-7044] Host key can be specified via SSH connection extras. (#12944)``
`295d66f914 <https://github.com/apache/airflow/commit/295d66f91446a69610576d040ba687b38f1c5d0a>`_  2020-12-30   ``Fix Grammar in PIP warning (#13380)``
`6cf76d7ac0 <https://github.com/apache/airflow/commit/6cf76d7ac01270930de7f105fb26428763ee1d4e>`_  2020-12-18   ``Fix typo in pip upgrade command :( (#13148)``
=================================================================================================  ===========  ================================================================================

1.0.0
.....

Latest change: 2020-12-09

=================================================================================================  ===========  ==================================================================================
Commit                                                                                             Committed    Subject
=================================================================================================  ===========  ==================================================================================
`32971a1a2d <https://github.com/apache/airflow/commit/32971a1a2de1db0b4f7442ed26facdf8d3b7a36f>`_  2020-12-09   ``Updates providers versions to 1.0.0 (#12955)``
`b40dffa085 <https://github.com/apache/airflow/commit/b40dffa08547b610162f8cacfa75847f3c4ca364>`_  2020-12-08   ``Rename remaing modules to match AIP-21 (#12917)``
`9b39f24780 <https://github.com/apache/airflow/commit/9b39f24780e85f859236672e9060b2fbeee81b36>`_  2020-12-08   ``Add support for dynamic connection form fields per provider (#12558)``
`c34ef853c8 <https://github.com/apache/airflow/commit/c34ef853c890e08f5468183c03dc8f3f3ce84af2>`_  2020-11-20   ``Separate out documentation building per provider  (#12444)``
`0080354502 <https://github.com/apache/airflow/commit/00803545023b096b8db4fbd6eb473843096d7ce4>`_  2020-11-18   ``Update provider READMEs for 1.0.0b2 batch release (#12449)``
`ae7cb4a1e2 <https://github.com/apache/airflow/commit/ae7cb4a1e2a96351f1976cf5832615e24863e05d>`_  2020-11-17   ``Update wrong commit hash in backport provider changes (#12390)``
`6889a333cf <https://github.com/apache/airflow/commit/6889a333cff001727eb0a66e375544a28c9a5f03>`_  2020-11-15   ``Improvements for operators and hooks ref docs (#12366)``
`7825e8f590 <https://github.com/apache/airflow/commit/7825e8f59034645ab3247229be83a3aa90baece1>`_  2020-11-13   ``Docs installation improvements (#12304)``
`dd2095f4a8 <https://github.com/apache/airflow/commit/dd2095f4a8b07c9b1a4c279a3578cd1e23b71a1b>`_  2020-11-10   ``Simplify string expressions & Use f-string (#12216)``
`85a18e13d9 <https://github.com/apache/airflow/commit/85a18e13d9dec84275283ff69e34704b60d54a75>`_  2020-11-09   ``Point at pypi project pages for cross-dependency of provider packages (#12212)``
`59eb5de78c <https://github.com/apache/airflow/commit/59eb5de78c70ee9c7ae6e4cba5c7a2babb8103ca>`_  2020-11-09   ``Update provider READMEs for up-coming 1.0.0beta1 releases (#12206)``
`b2a28d1590 <https://github.com/apache/airflow/commit/b2a28d1590410630d66966aa1f2b2a049a8c3b32>`_  2020-11-09   ``Moves provider packages scripts to dev (#12082)``
`41bf172c1d <https://github.com/apache/airflow/commit/41bf172c1dc75099f4f9d8b3f3350b4b1f523ef9>`_  2020-11-04   ``Simplify string expressions (#12093)``
`4e8f9cc8d0 <https://github.com/apache/airflow/commit/4e8f9cc8d02b29c325b8a5a76b4837671bdf5f68>`_  2020-11-03   ``Enable Black - Python Auto Formmatter (#9550)``
`8c42cf1b00 <https://github.com/apache/airflow/commit/8c42cf1b00c90f0d7f11b8a3a455381de8e003c5>`_  2020-11-03   ``Use PyUpgrade to use Python 3.6 features (#11447)``
`5a439e84eb <https://github.com/apache/airflow/commit/5a439e84eb6c0544dc6c3d6a9f4ceeb2172cd5d0>`_  2020-10-26   ``Prepare providers release 0.0.2a1 (#11855)``
`872b1566a1 <https://github.com/apache/airflow/commit/872b1566a11cb73297e657ff325161721b296574>`_  2020-10-25   ``Generated backport providers readmes/setup for 2020.10.29 (#11826)``
`349b0811c3 <https://github.com/apache/airflow/commit/349b0811c3022605426ba57d30936240a7c2848a>`_  2020-10-20   ``Add D200 pydocstyle check (#11688)``
`16e7129719 <https://github.com/apache/airflow/commit/16e7129719f1c0940aef2a93bed81368e997a746>`_  2020-10-13   ``Added support for provider packages for Airflow 2.0 (#11487)``
`27e637fbe3 <https://github.com/apache/airflow/commit/27e637fbe3f17737e898774ff151448f4f0aa129>`_  2020-10-09   ``Bugfix: Error in SSHOperator when command is None (#11361)``
`0a0e1af800 <https://github.com/apache/airflow/commit/0a0e1af80038ef89974c3c8444461fe867945daa>`_  2020-10-03   ``Fix Broken Markdown links in Providers README TOC (#11249)``
`ca4238eb4d <https://github.com/apache/airflow/commit/ca4238eb4d9a2aef70eb641343f59ee706d27d13>`_  2020-10-02   ``Fixed month in backport packages to October (#11242)``
`5220e4c384 <https://github.com/apache/airflow/commit/5220e4c3848a2d2c81c266ef939709df9ce581c5>`_  2020-10-02   ``Prepare Backport release 2020.09.07 (#11238)``
`b6d5d1e985 <https://github.com/apache/airflow/commit/b6d5d1e985ffc19867647ea0b35fa14c2cdfb59a>`_  2020-10-01   ``Strict type checking for SSH (#11216)``
`68fa29bff0 <https://github.com/apache/airflow/commit/68fa29bff0203bc02b85ef93b7617770219c260a>`_  2020-09-25   ``Added support for encrypted private keys in SSHHook (#11097)``
`f3e87c5030 <https://github.com/apache/airflow/commit/f3e87c503081a3085dff6c7352640d7f08beb5bc>`_  2020-09-22   ``Add D202 pydocstyle check (#11032)``
`9549274d11 <https://github.com/apache/airflow/commit/9549274d110f689a0bd709db829a4d69e274eed9>`_  2020-09-09   ``Upgrade black to 20.8b1 (#10818)``
`fdd9b6f65b <https://github.com/apache/airflow/commit/fdd9b6f65b608c516b8a062b058972d9a45ec9e3>`_  2020-08-25   ``Enable Black on Providers Packages (#10543)``
`3696c34c28 <https://github.com/apache/airflow/commit/3696c34c28c6bc7b442deab999d9ecba24ed0e34>`_  2020-08-24   ``Fix typo in the word "release" (#10528)``
`ee7ca128a1 <https://github.com/apache/airflow/commit/ee7ca128a17937313566f2badb6cc569c614db94>`_  2020-08-22   ``Fix broken Markdown refernces in Providers README (#10483)``
`cdec301254 <https://github.com/apache/airflow/commit/cdec3012542b45d23a05f62d69110944ba542e2a>`_  2020-08-07   ``Add correct signature to all operators and sensors (#10205)``
`aeea71274d <https://github.com/apache/airflow/commit/aeea71274d4527ff2351102e94aa38bda6099e7f>`_  2020-08-02   ``Remove 'args' parameter from provider operator constructors (#10097)``
`2248a5da1d <https://github.com/apache/airflow/commit/2248a5da1d83ca901ec24d5809e718bbbd2c3894>`_  2020-06-29   ``Expose option: look_for_keys in ssh_hook via extras (#8793)``
`d0e7db4024 <https://github.com/apache/airflow/commit/d0e7db4024806af35e3c9a2cae460fdeedd4d2ec>`_  2020-06-19   ``Fixed release number for fresh release (#9408)``
`12af6a0800 <https://github.com/apache/airflow/commit/12af6a08009b8776e00d8a0aab92363eb8c4e8b1>`_  2020-06-19   ``Final cleanup for 2020.6.23rc1 release preparation (#9404)``
`c7e5bce57f <https://github.com/apache/airflow/commit/c7e5bce57fe7f51cefce4f8a41ce408ac5675d13>`_  2020-06-19   ``Prepare backport release candidate for 2020.6.23rc1 (#9370)``
`f6bd817a3a <https://github.com/apache/airflow/commit/f6bd817a3aac0a16430fc2e3d59c1f17a69a15ac>`_  2020-06-16   ``Introduce 'transfers' packages (#9320)``
`0b0e4f7a4c <https://github.com/apache/airflow/commit/0b0e4f7a4cceff3efe15161fb40b984782760a34>`_  2020-05-26   ``Preparing for RC3 relase of backports (#9026)``
`00642a46d0 <https://github.com/apache/airflow/commit/00642a46d019870c4decb3d0e47c01d6a25cb88c>`_  2020-05-26   ``Fixed name of 20 remaining wrongly named operators. (#8994)``
`375d1ca229 <https://github.com/apache/airflow/commit/375d1ca229464617780623c61c6e8a1bf570c87f>`_  2020-05-19   ``Release candidate 2 for backport packages 2020.05.20 (#8898)``
`12c5e5d8ae <https://github.com/apache/airflow/commit/12c5e5d8ae25fa633efe63ccf4db389e2b796d79>`_  2020-05-17   ``Prepare release candidate for backport packages (#8891)``
`f3521fb0e3 <https://github.com/apache/airflow/commit/f3521fb0e36733d8bd356123e56a453fd37a6dca>`_  2020-05-16   ``Regenerate readme files for backport package release (#8886)``
`92585ca4cb <https://github.com/apache/airflow/commit/92585ca4cb375ac879f4ab331b3a063106eb7b92>`_  2020-05-15   ``Added automated release notes generation for backport operators (#8807)``
`21cc7d7298 <https://github.com/apache/airflow/commit/21cc7d729827e9f3af0698bf647b2d41fc87b11c>`_  2020-05-10   ``Document default timeout value for SSHOperator (#8744)``
`4bde99f132 <https://github.com/apache/airflow/commit/4bde99f1323d72f6c84c1548079d5e98fc0a2a9a>`_  2020-03-23   ``Make airflow/providers pylint compatible (#7802)``
`74c2a6ded4 <https://github.com/apache/airflow/commit/74c2a6ded4d615de8e1b1c04a25146344138e920>`_  2020-03-23   ``Add call to Super class in 'ftp' & 'ssh' providers (#7822)``
`df24b43370 <https://github.com/apache/airflow/commit/df24b43370ca5812273ecd91d35104e023a407e6>`_  2020-02-14   ``[AIRFLOW-6800] Close file object after parsing ssh config (#7415)``
`97a429f9d0 <https://github.com/apache/airflow/commit/97a429f9d0cf740c5698060ad55f11e93cb57b55>`_  2020-02-02   ``[AIRFLOW-6714] Remove magic comments about UTF-8 (#7338)``
`9a04013b0e <https://github.com/apache/airflow/commit/9a04013b0e40b0d744ff4ac9f008491806d60df2>`_  2020-01-27   ``[AIRFLOW-6646][AIP-21] Move protocols classes to providers package (#7268)``
=================================================================================================  ===========  ==================================================================================
