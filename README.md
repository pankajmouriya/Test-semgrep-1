# ![Juice Shop Logo](https://raw.githubusercontent.com/juice-shop/juice-shop/master/frontend/src/assets/public/images/JuiceShop_Logo_100px.png) OWASP Juice Shop
![Security Assessment Badge](https://img.shields.io/badge/Security%20Assessment-Medium-yellow?&logoColor=white)
![Generic Badge](https://img.shields.io/badge/Pentest-Pentest-yellowgreen)
[![OWASP Flagship](https://img.shields.io/badge/owasp-flagship%20project-48A646.svg)](https://owasp.org/projects/#sec-flagships)
[![GitHub release](https://img.shields.io/github/release/juice-shop/juice-shop.svg)](https://github.com/juice-shop/juice-shop/releases/latest)
[![Twitter Follow](https://img.shields.io/twitter/follow/owasp_juiceshop.svg?style=social&label=Follow)](https://twitter.com/owasp_juiceshop)
[![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/owasp_juiceshop?style=social)](https://reddit.com/r/owasp_juiceshop)


<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg">
<foreignObject width="100" height="100">
    <div xmlns="http://www.w3.org/1999/xhtml">
         <nav class="navbar navbar-default" role="navigation">
          <div class="navbar-header" style="float: none"><a class="navbar-brand" href="#"><svg
                xmlns="http://www.w3.org/2000/svg" version="1.1" width="52" height="52" id="svg2">
                <g transform="matrix(0.75266991,0,0,0.75266991,-17.752968,-104.57468)" id="g32">
                  <path
                    d="m 24.7,173.5 c 0,-9 3.5,-17.5 9.9,-23.9 6.8,-6.8 15.7,-10.4 25,-10 8.6,0.3 16.9,3.9 22.9,9.8 6.4,6.4 9.9,14.9 10,23.8 0.1,9.1 -3.5,17.8 -10,24.3 -13.2,13.2 -34.7,13.1 -48,-0.1 -1.5,-1.5 -1.9,-4.2 0.2,-6.2 l 9,-9 c -2,-3.6 -4.9,-13.1 2.6,-20.7 7.6,-7.6 18.6,-6 24.4,-0.2 3.3,3.3 5.1,7.6 5.1,12.1 0.1,4.6 -1.8,9.1 -5.3,12.5 -4.2,4.2 -10.2,5.8 -16.1,4.4 -1.5,-0.4 -2.4,-1.9 -2.1,-3.4 0.4,-1.5 1.9,-2.4 3.4,-2.1 4.1,1 8,-0.1 10.9,-2.9 2.3,-2.3 3.6,-5.3 3.6,-8.4 0,0 0,-0.1 0,-0.1 0,-3 -1.3,-5.9 -3.5,-8.2 -3.9,-3.9 -11.3,-4.9 -16.5,0.2 -6.3,6.3 -1.6,14.1 -1.6,14.2 1.5,2.4 0.7,5 -0.9,6.3 l -8.4,8.4 c 9.9,8.9 27.2,11.2 39.1,-0.8 5.4,-5.4 8.4,-12.5 8.4,-20 0,-0.1 0,-0.2 0,-0.3 -0.1,-7.5 -3,-14.6 -8.4,-19.9 -5,-5 -11.9,-8 -19.1,-8.2 -7.8,-0.3 -15.2,2.7 -20.9,8.4 -8.7,8.7 -8.7,19 -7.9,24.3 0.3,2.4 1.1,4.9 2.2,7.3 0.6,1.4 0,3.1 -1.4,3.7 -1.4,0.6 -3.1,0 -3.7,-1.4 -1.3,-2.9 -2.2,-5.8 -2.6,-8.7 -0.3,-1.7 -0.4,-3.5 -0.4,-5.2 z"
                    id="path34" style="fill:#12497f"></path>
                </g>
              </svg></a>
            <div>
              <h1>OpenSCAP Evaluation Report</h1>
            </div>
          </div>
        </nav>
        <div class="container">
          <div id="content">
            <div id="introduction">
              <div class="row">
                <h2>Guide to the Secure Configuration of Ubuntu 20.04</h2>
                <blockquote>with profile <mark>CIS Ubuntu 20.04 Level 1 Server Benchmark</mark>
                  <div class="col-md-12 well well-lg horizontal-scroll">
                    <div class="description profile-description"><small>This baseline aligns to the Center for Internet
                        Security
                        Ubuntu 20.04 LTS Benchmark, v1.0.0, released 07-21-2020.</small></div>
                  </div>
                </blockquote>
                <div class="col-md-12 well well-lg horizontal-scroll">
                  <div class="front-matter">The SCAP Security Guide Project<br>

                    <a
                      href="https://www.open-scap.org/security-policies/scap-security-guide">https://www.open-scap.org/security-policies/scap-security-guide</a>
                  </div>
                  <div class="description">This guide presents a catalog of security-relevant
                    configuration settings for Ubuntu 20.04. It is a rendering of
                    content structured in the eXtensible Configuration Checklist Description Format (XCCDF)
                    in order to support security automation. The SCAP content is
                    is available in the <code>scap-security-guide</code> package which is developed at

                    <a
                      href="https://www.open-scap.org/security-policies/scap-security-guide">https://www.open-scap.org/security-policies/scap-security-guide</a>.
                    <br><br>
                    Providing system administrators with such guidance informs them how to securely
                    configure systems under their control in a variety of network roles. Policy
                    makers and baseline creators can use this catalog of settings, with its
                    associated references to higher-level security control catalogs, in order to
                    assist them in security baseline creation. This guide is a <em>catalog, not a
                      checklist</em>, and satisfaction of every item is not likely to be possible or
                    sensible in many operational scenarios. However, the XCCDF format enables
                    granular selection and adjustment of settings, and their association with OVAL
                    and OCIL content provides an automated checking capability. Transformations of
                    this document, and its associated automated checking content, are capable of
                    providing baselines that meet a diverse set of policy objectives. Some example
                    XCCDF <em>Profiles</em>, which are selections of items that form checklists and
                    can be used as baselines, are available with this guide. They can be
                    processed, in an automated fashion, with tools that support the Security
                    Content Automation Protocol (SCAP). The DISA STIG, which provides required
                    settings for US Department of Defense systems, is one example of a baseline
                    created from this guidance.
                  </div>
                  <div class="top-spacer-10">
                    <div class="alert alert-info">Do not attempt to implement any of the settings in
                      this guide without first testing them in a non-operational environment. The
                      creators of this guidance assume no responsibility whatsoever for its use by
                      other parties, and makes no guarantees, expressed or implied, about its
                      quality, reliability, or any other characteristic.
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div id="characteristics">
              <h2>Evaluation Characteristics</h2>
              <div class="row">
                <div class="col-md-5 well well-lg horizontal-scroll">
                  <table class="table table-bordered">
                    <tr>
                      <th>Evaluation target</th>
                      <td>iv-stage-bastion-52-66-137-180</td>
                    </tr>
                    <tr>
                      <th>Benchmark URL</th>
                      <td>/usr/share/xml/scap/ssg/content/ssg-ubuntu2004-ds.xml</td>
                    </tr>
                    <tr>
                      <th>Benchmark ID</th>
                      <td>xccdf_org.ssgproject.content_benchmark_UBUNTU_20-04</td>
                    </tr>
                    <tr>
                      <th>Profile ID</th>
                      <td>xccdf_org.ssgproject.content_profile_cis_level1_server</td>
                    </tr>
                    <tr>
                      <th>Started at</th>
                      <td>2022-04-25T04:27:06</td>
                    </tr>
                    <tr>
                      <th>Finished at</th>
                      <td>2022-04-25T04:27:51</td>
                    </tr>
                    <tr>
                      <th>Performed by</th>
                      <td>pankaj</td>
                    </tr>
                  </table>
                </div>
                <div class="col-md-3 horizontal-scroll">
                  <h4>CPE Platforms</h4>
                  <ul class="list-group">
                    <li class="list-group-item"><span class="label label-success"
                        title="CPE platform cpe:/o:canonical:ubuntu_linux:20.04::~~lts~~~ was found applicable on the evaluated machine">cpe:/o:canonical:ubuntu_linux:20.04::~~lts~~~</span>
                    </li>
                  </ul>
                </div>
                <div class="col-md-4 horizontal-scroll">
                  <h4>Addresses</h4>
                  <ul class="list-group">
                    <li class="list-group-item"><span class="label label-primary">IPv4</span>
                      127.0.0.1</li>
                    <li class="list-group-item"><span class="label label-primary">IPv4</span>
                      10.0.1.163</li>
                    <li class="list-group-item"><span class="label label-info">IPv6</span>
                      0:0:0:0:0:0:0:1</li>
                    <li class="list-group-item"><span class="label label-info">IPv6</span>
                      fe80:0:0:0:99:eff:fe24:d68e</li>
                    <li class="list-group-item"><span class="label label-default">MAC</span>
                      00:00:00:00:00:00</li>
                    <li class="list-group-item"><span class="label label-default">MAC</span>
                      02:99:0E:24:D6:8E</li>
                  </ul>
                </div>
              </div>
            </div>
            <div id="compliance-and-scoring">
              <h2>Compliance and Scoring</h2>
              <div class="alert alert-danger"><strong>The target system did not satisfy the conditions of 76
                  rules!</strong>
                Furthermore, the results of 7 rules were inconclusive.

                Please review rule results and consider applying remediation.
              </div>
              <h3>Rule results</h3>
              <div class="progress"
                title="Displays proportion of passed/fixed, failed/error, and other rules (in that order). There were 186 rules taken into account.">
                <div class="progress-bar progress-bar-success" style="width: 53.763440860215%">100 passed
                </div>
                <div class="progress-bar progress-bar-danger" style="width: 40.8602150537634%">76 failed
                </div>
                <div class="progress-bar progress-bar-warning" style="width: 5.376344086021501%">10 other
                </div>
              </div>
              <h3>Severity of failed rules</h3>
              <div class="progress"
                title="Displays proportion of high, medium, low, and other severity failed rules (in that order). There were 76 total failed rules.">
                <div class="progress-bar progress-bar-success" style="width: 3.947368421052631%">3 other
                </div>
                <div class="progress-bar progress-bar-info" style="width: 9.210526315789473%">7 low
                </div>
                <div class="progress-bar progress-bar-warning" style="width: 85.5263157894737%">65 medium
                </div>
                <div class="progress-bar progress-bar-danger" style="width: 1.31578947368421%">1 high
                </div>
              </div>
              <h3 title="As per the XCCDF specification">Score</h3>
              <table class="table table-striped table-bordered">
                <thead>
                  <tr>
                    <th>Scoring system</th>
                    <th class="text-center">Score</th>
                    <th class="text-center">Maximum</th>
                    <th class="text-center" style="width: 40%">Percent</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td>urn:xccdf:scoring:default</td>
                    <td class="text-center">64.768562</td>
                    <td class="text-center">100.000000</td>
                    <td>
                      <div class="progress">
                        <div class="progress-bar progress-bar-success" style="width: 64.768562%">64.77%</div>
                        <div class="progress-bar progress-bar-danger" style="width: 35.231438%"></div>
                      </div>
                    </td>
                  </tr>
                </tbody>
              </table>
            </div>
            <div id="rule-overview">
              <h2>Rule Overview</h2>
              <div class="form-group js-only hidden-print">
                <div class="row">
                  <div title="Filter rules by their XCCDF result">
                    <div class="col-sm-2 toggle-rule-display-success">
                      <div class="checkbox"><label><input class="toggle-rule-display" type="checkbox"
                            onclick="toggleRuleDisplay(this)" checked value="pass"></input>pass</label></div>
                      <div class="checkbox"><label><input class="toggle-rule-display" type="checkbox"
                            onclick="toggleRuleDisplay(this)" checked value="fixed"></input>fixed</label></div>
                      <div class="checkbox"><label><input class="toggle-rule-display" type="checkbox"
                            onclick="toggleRuleDisplay(this)" checked
                            value="informational"></input>informational</label></div>
                    </div>
                    <div class="col-sm-2 toggle-rule-display-danger">
                      <div class="checkbox"><label><input class="toggle-rule-display" type="checkbox"
                            onclick="toggleRuleDisplay(this)" checked value="fail"></input>fail</label></div>
                      <div class="checkbox"><label><input class="toggle-rule-display" type="checkbox"
                            onclick="toggleRuleDisplay(this)" checked value="error"></input>error</label></div>
                      <div class="checkbox"><label><input class="toggle-rule-display" type="checkbox"
                            onclick="toggleRuleDisplay(this)" checked value="unknown"></input>unknown</label></div>
                    </div>
                    <div class="col-sm-2 toggle-rule-display-other">
                      <div class="checkbox"><label><input class="toggle-rule-display" type="checkbox"
                            onclick="toggleRuleDisplay(this)" checked value="notchecked"></input>notchecked</label>
                      </div>
                      <div class="checkbox"><label><input class="toggle-rule-display" type="checkbox"
                            onclick="toggleRuleDisplay(this)" checked
                            value="notapplicable"></input>notapplicable</label></div>
                    </div>
                  </div>
                  <div class="col-sm-6">
                    <div class="input-group"><input type="text" class="form-control"
                        placeholder="Search through XCCDF rules" id="search-input" oninput="ruleSearch()"></input>
                      <div class="input-group-btn"><button class="btn btn-default"
                          onclick="ruleSearch()">Search</button></div>
                    </div>
                    <p id="search-matches"></p>
                    Group rules by:
                    <select name="groupby" onchange="groupRulesBy(value)">
                      <option value="default" selected>Default</option>
                      <option value="severity">Severity</option>
                      <option value="result">Result</option>
                      <option disabled>──────────</option>
                      <option value="NIST SP 800-171">NIST SP 800-171</option>
                      <option value="NIST SP 800-53">NIST SP 800-53</option>
                      <option value="http://www.ssi.gouv.fr/administration/bonnes-pratiques/">
                        http://www.ssi.gouv.fr/administration/bonnes-pratiques/</option>
                      <option value="https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf">
                        https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf</option>
                      <option value="https://public.cyber.mil/stigs/cci/">https://public.cyber.mil/stigs/cci/</option>
                      <option
                        value="https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os">
                        https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os
                      </option>
                      <option
                        value="https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux">
                        https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux
                      </option>
                      <option value="https://www.cisecurity.org/benchmark/ubuntu_linux/">
                        https://www.cisecurity.org/benchmark/ubuntu_linux/</option>
                      <option value="https://www.cisecurity.org/controls/">https://www.cisecurity.org/controls/</option>
                      <option value="FBI CJIS">FBI CJIS</option>
                      <option
                        value="https://www.gpo.gov/fdsys/pkg/CFR-2007-title45-vol1/pdf/CFR-2007-title45-vol1-chapA-subchapC.pdf">
                        https://www.gpo.gov/fdsys/pkg/CFR-2007-title45-vol1/pdf/CFR-2007-title45-vol1-chapA-subchapC.pdf
                      </option>
                      <option value="https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu">
                        https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu</option>
                      <option value="https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat">
                        https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat</option>
                      <option value="https://www.isaca.org/resources/cobit">https://www.isaca.org/resources/cobit
                      </option>
                      <option value="https://www.iso.org/standard/54534.html">https://www.iso.org/standard/54534.html
                      </option>
                      <option
                        value="https://www.nerc.com/pa/Stand/Standard%20Purpose%20Statement%20DL/US_Standard_One-Stop-Shop.xlsx">
                        https://www.nerc.com/pa/Stand/Standard%20Purpose%20Statement%20DL/US_Standard_One-Stop-Shop.xlsx
                      </option>
                      <option value="https://www.niap-ccevs.org/Profile/PP.cfm">
                        https://www.niap-ccevs.org/Profile/PP.cfm</option>
                      <option value="PCI-DSS Requirement">PCI-DSS Requirement</option>
                    </select>
                  </div>
                </div>
              </div>
              <table class="treetable table table-bordered">
                <thead>
                  <tr>
                    <th>Title</th>
                    <th style="width: 120px; text-align: center">Severity</th>
                    <th style="width: 120px; text-align: center">Result</th>
                  </tr>
                </thead>
                <tbody>
                  <tr data-tt-id="xccdf_org.ssgproject.content_benchmark_UBUNTU_20-04"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_benchmark_UBUNTU_20-04">
                    <td colspan="3" style="padding-left: 0px"><strong>Guide to the Secure Configuration of Ubuntu
                        20.04</strong> <span class="badge">76x fail</span> <span class="badge">7x error</span> <span
                        class="badge">3x notchecked</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_system"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_system"
                    data-tt-parent-id="xccdf_org.ssgproject.content_benchmark_UBUNTU_20-04">
                    <td colspan="3" style="padding-left: 19px"><strong>System Settings</strong> <span class="badge">63x
                        fail</span> <span class="badge">5x error</span> <span class="badge">2x notchecked</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_software"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_software"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_system">
                    <td colspan="3" style="padding-left: 38px"><strong>Installing and Maintaining Software</strong>
                      <span class="badge">4x fail</span> <span class="badge">2x error</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_integrity"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_integrity"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_software">
                    <td colspan="3" style="padding-left: 57px"><strong>System and Software Integrity</strong> <span
                        class="badge">3x fail</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_software-integrity"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_software-integrity"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_integrity">
                    <td colspan="3" style="padding-left: 76px"><strong>Software Integrity Checking</strong> <span
                        class="badge">3x fail</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_aide"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_aide"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_software-integrity">
                    <td colspan="3" style="padding-left: 95px"><strong>Verify Integrity with AIDE</strong> <span
                        class="badge">3x fail</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_package_aide_installed"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66694" data-tt-parent-id="xccdf_org.ssgproject.content_group_aide"
                    data-references='{"":["1034","1288","1341","1417"],"NIST SP 800-53":["CM-6(a)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R51)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["DE.CM-1","DE.CM-7","PR.DS-1","PR.DS-6","PR.DS-8","PR.IP-1","PR.IP-3"],"https://public.cyber.mil/stigs/cci/":["CCI-002696","CCI-002699","CCI-001744"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000363-GPOS-00150","SRG-OS-000445-GPOS-00199"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux":["UBTU-20-010450"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.4.1"],"https://www.cisecurity.org/controls/":["1","11","12","13","14","15","16","2","3","5","7","8","9"],"FBI CJIS":["5.10.1.3"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 3.1","SR 3.3","SR 3.4","SR 3.8","SR 4.1","SR 6.2","SR 7.6"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.4.3.2","4.3.4.3.3","4.3.4.4.4"],"https://www.isaca.org/resources/cobit":["APO01.06","BAI01.06","BAI02.01","BAI03.05","BAI06.01","BAI10.01","BAI10.02","BAI10.03","BAI10.05","DSS01.03","DSS03.05","DSS04.07","DSS05.02","DSS05.03","DSS05.05","DSS05.07","DSS06.02","DSS06.06"],"https://www.iso.org/standard/54534.html":["A.11.2.4","A.12.1.2","A.12.2.1","A.12.4.1","A.12.5.1","A.12.6.2","A.14.1.2","A.14.1.3","A.14.2.2","A.14.2.3","A.14.2.4","A.14.2.7","A.15.2.1","A.8.2.3"],"PCI-DSS Requirement":["Req-11.5"]}'>
                    <td style="padding-left: 114px"><a href="#rule-detail-idm66694"
                        onclick="return openRuleDetailsDialog('idm66694')">Install AIDE</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_aide_build_database"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66698" data-tt-parent-id="xccdf_org.ssgproject.content_group_aide"
                    data-references='{"NIST SP 800-53":["CM-6(a)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R51)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["DE.CM-1","DE.CM-7","PR.DS-1","PR.DS-6","PR.DS-8","PR.IP-1","PR.IP-3"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.4.1"],"https://www.cisecurity.org/controls/":["1","11","12","13","14","15","16","2","3","5","7","8","9"],"FBI CJIS":["5.10.1.3"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 3.1","SR 3.3","SR 3.4","SR 3.8","SR 4.1","SR 6.2","SR 7.6"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.4.3.2","4.3.4.3.3","4.3.4.4.4"],"https://www.isaca.org/resources/cobit":["APO01.06","BAI01.06","BAI02.01","BAI03.05","BAI06.01","BAI10.01","BAI10.02","BAI10.03","BAI10.05","DSS01.03","DSS03.05","DSS04.07","DSS05.02","DSS05.03","DSS05.05","DSS05.07","DSS06.02","DSS06.06"],"https://www.iso.org/standard/54534.html":["A.11.2.4","A.12.1.2","A.12.2.1","A.12.4.1","A.12.5.1","A.12.6.2","A.14.1.2","A.14.1.3","A.14.2.2","A.14.2.3","A.14.2.4","A.14.2.7","A.15.2.1","A.8.2.3"],"PCI-DSS Requirement":["Req-11.5"]}'>
                    <td style="padding-left: 114px"><a href="#rule-detail-idm66698"
                        onclick="return openRuleDetailsDialog('idm66698')">Build and Test AIDE Database</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_aide_periodic_cron_checking"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66704" data-tt-parent-id="xccdf_org.ssgproject.content_group_aide"
                    data-references='{"NIST SP 800-53":["SI-7","SI-7(1)","CM-6(a)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R51)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["DE.CM-1","DE.CM-7","PR.DS-1","PR.DS-6","PR.DS-8","PR.IP-1","PR.IP-3"],"https://public.cyber.mil/stigs/cci/":["CCI-001744","CCI-002699","CCI-002702"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000363-GPOS-00150","SRG-OS-000446-GPOS-00200","SRG-OS-000447-GPOS-00201"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux":["UBTU-20-010074"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.4.2"],"https://www.cisecurity.org/controls/":["1","11","12","13","14","15","16","2","3","5","7","8","9"],"FBI CJIS":["5.10.1.3"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 3.1","SR 3.3","SR 3.4","SR 3.8","SR 4.1","SR 6.2","SR 7.6"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.4.3.2","4.3.4.3.3","4.3.4.4.4"],"https://www.isaca.org/resources/cobit":["APO01.06","BAI01.06","BAI02.01","BAI03.05","BAI06.01","BAI10.01","BAI10.02","BAI10.03","BAI10.05","DSS01.03","DSS03.05","DSS04.07","DSS05.02","DSS05.03","DSS05.05","DSS05.07","DSS06.02","DSS06.06"],"https://www.iso.org/standard/54534.html":["A.11.2.4","A.12.1.2","A.12.2.1","A.12.4.1","A.12.5.1","A.12.6.2","A.14.1.2","A.14.1.3","A.14.2.2","A.14.2.3","A.14.2.4","A.14.2.7","A.15.2.1","A.8.2.3"],"PCI-DSS Requirement":["Req-11.5"]}'>
                    <td style="padding-left: 114px"><a href="#rule-detail-idm66704"
                        onclick="return openRuleDetailsDialog('idm66704')">Configure Periodic Execution of AIDE</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_disable_prelink"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_disable_prelink"
                    id="rule-overview-leaf-idm66690" data-tt-parent-id="xccdf_org.ssgproject.content_group_integrity"
                    data-references='{"":["SRG-OS-000120-VMM-000600","SRG-OS-000478-VMM-001980","SRG-OS-000396-VMM-001590"],"NIST SP 800-171":["3.13.11"],"NIST SP 800-53":["SC-13","CM-6(a)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.DS-1","PR.DS-6","PR.DS-8","PR.IP-1"],"https://public.cyber.mil/stigs/cci/":["CCI-000803","CCI-002450"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.6.3"],"https://www.cisecurity.org/controls/":["11","13","14","2","3","9"],"FBI CJIS":["5.10.1.3"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 3.1","SR 3.3","SR 3.4","SR 3.8","SR 4.1","SR 7.6"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.4.3.2","4.3.4.3.3","4.3.4.4.4"],"https://www.isaca.org/resources/cobit":["APO01.06","BAI02.01","BAI03.05","BAI06.01","BAI10.01","BAI10.02","BAI10.03","BAI10.05","DSS04.07","DSS05.03","DSS06.02","DSS06.06"],"https://www.iso.org/standard/54534.html":["A.11.2.4","A.12.1.2","A.12.2.1","A.12.5.1","A.12.6.2","A.14.1.2","A.14.1.3","A.14.2.2","A.14.2.3","A.14.2.4","A.8.2.3"],"https://www.nerc.com/pa/Stand/Standard%20Purpose%20Statement%20DL/US_Standard_One-Stop-Shop.xlsx":["CIP-003-8 R4.2","CIP-007-3 R5.1"],"PCI-DSS Requirement":["Req-11.5"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm66690"
                        onclick="return openRuleDetailsDialog('idm66690')">Disable Prelinking</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_disk_partitioning"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_disk_partitioning"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_software">
                    <td colspan="3" style="padding-left: 57px"><strong>Disk Partitioning</strong> <span class="badge">1x
                        fail</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_partition_for_tmp"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66726"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_disk_partitioning"
                    data-references='{"NIST SP 800-53":["CM-6(a)","SC-5(2)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R12)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.PT-4"],"https://public.cyber.mil/stigs/cci/":["CCI-000366"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00227"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.1.2"],"https://www.cisecurity.org/controls/":["12","15","8"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 3.1","SR 3.5","SR 3.8","SR 4.1","SR 4.3","SR 5.1","SR 5.2","SR 5.3","SR 7.1","SR 7.6"],"https://www.isaca.org/resources/cobit":["APO13.01","DSS05.02"],"https://www.iso.org/standard/54534.html":["A.13.1.1","A.13.2.1","A.14.1.3"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm66726"
                        onclick="return openRuleDetailsDialog('idm66726')">Ensure /tmp Located On Separate Partition</a>
                    </td>
                    <td class="rule-severity" style="text-align: center">low</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_gnome"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_gnome"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_software">
                    <td colspan="3" style="padding-left: 57px">GNOME Desktop Environment
                      <script>$(document).ready(function () { $('.treetable').treetable("collapseNode", "xccdf_org.ssgproject.content_group_gnome"); });</script>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_package_gdm_removed"
                    class="rule-overview-leaf rule-overview-leaf-notapplicable rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_package_gdm_removed"
                    id="rule-overview-leaf-idm66738" data-tt-parent-id="xccdf_org.ssgproject.content_group_gnome"
                    data-references='{"NIST SP 800-53":["CM-7(a)","CM-7(b)","CM-6(a)"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00227"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.10"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm66738"
                        onclick="return openRuleDetailsDialog('idm66738')">Remove the GDM Package Group</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-notapplicable">
                      <div><abbr
                          title="The Rule was not applicable to the target of the test. For example, the Rule might have been specific to a different version of the target OS, or it might have been a test against a platform feature that was not installed.">notapplicable</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_sudo"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_sudo"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_software">
                    <td colspan="3" style="padding-left: 57px"><strong>Sudo</strong> <span class="badge">2x error</span>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_package_sudo_installed"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_package_sudo_installed"
                    id="rule-overview-leaf-idm66750" data-tt-parent-id="xccdf_org.ssgproject.content_group_sudo"
                    data-references='{"":["1382","1384","1386"],"NIST SP 800-53":["CM-6(a)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R19)"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000324-GPOS-00125"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.3.1"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm66750"
                        onclick="return openRuleDetailsDialog('idm66750')">Install sudo Package</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_sudo_add_use_pty"
                    class="rule-overview-leaf rule-overview-leaf-error rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66758" data-tt-parent-id="xccdf_org.ssgproject.content_group_sudo"
                    data-references='{"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R58)"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.3.2"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm66758"
                        onclick="return openRuleDetailsDialog('idm66758')">Ensure Only Users Logged In To Real tty Can
                        Execute Sudo - sudo use_pty</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-error">
                      <div><abbr
                          title="The checking engine could not complete the evaluation, therefore the status of the target's compliance with the rule is not certain. This could happen, for example, if a testing tool was run with insufficient privileges and could not gather all of the necessary information.">error</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_sudo_custom_logfile"
                    class="rule-overview-leaf rule-overview-leaf-error rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66762" data-tt-parent-id="xccdf_org.ssgproject.content_group_sudo"
                    data-references='{"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.3.3"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm66762"
                        onclick="return openRuleDetailsDialog('idm66762')">Ensure Sudo Logfile Exists - sudo logfile</a>
                    </td>
                    <td class="rule-severity" style="text-align: center">low</td>
                    <td class="rule-result rule-result-error">
                      <div><abbr
                          title="The checking engine could not complete the evaluation, therefore the status of the target's compliance with the rule is not certain. This could happen, for example, if a testing tool was run with insufficient privileges and could not gather all of the necessary information.">error</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_accounts"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_accounts"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_system">
                    <td colspan="3" style="padding-left: 38px"><strong>Account and Access Control</strong> <span
                        class="badge">21x fail</span> <span class="badge">1x error</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_accounts-banners"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_accounts-banners"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts">
                    <td colspan="3" style="padding-left: 57px">Warning Banners for System Accesses
                      <script>$(document).ready(function () { $('.treetable').treetable("collapseNode", "xccdf_org.ssgproject.content_group_accounts-banners"); });</script>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_file_groupowner_etc_issue"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_file_groupowner_etc_issue"
                    id="rule-overview-leaf-idm66789"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-banners"
                    data-references='{"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.8.1.5"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm66789"
                        onclick="return openRuleDetailsDialog('idm66789')">Verify Group Ownership of System Login
                        Banner</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_file_groupowner_etc_motd"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_file_groupowner_etc_motd"
                    id="rule-overview-leaf-idm66793"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-banners"
                    data-references='{"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.8.1.4"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm66793"
                        onclick="return openRuleDetailsDialog('idm66793')">Verify Group Ownership of Message of the Day
                        Banner</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_file_owner_etc_issue"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_file_owner_etc_issue"
                    id="rule-overview-leaf-idm66797"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-banners"
                    data-references='{"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.8.1.5"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm66797"
                        onclick="return openRuleDetailsDialog('idm66797')">Verify ownership of System Login Banner</a>
                    </td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_file_owner_etc_motd"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_file_owner_etc_motd"
                    id="rule-overview-leaf-idm66801"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-banners"
                    data-references='{"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.8.1.4"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm66801"
                        onclick="return openRuleDetailsDialog('idm66801')">Verify ownership of Message of the Day
                        Banner</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_file_permissions_etc_issue"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_file_permissions_etc_issue"
                    id="rule-overview-leaf-idm66805"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-banners"
                    data-references='{"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.8.1.5"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm66805"
                        onclick="return openRuleDetailsDialog('idm66805')">Verify permissions on System Login Banner</a>
                    </td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_file_permissions_etc_motd"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_file_permissions_etc_motd"
                    id="rule-overview-leaf-idm66809"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-banners"
                    data-references='{"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.8.1.4"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm66809"
                        onclick="return openRuleDetailsDialog('idm66809')">Verify permissions on Message of the Day
                        Banner</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_accounts-pam"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_accounts-pam"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts">
                    <td colspan="3" style="padding-left: 57px"><strong>Protect Accounts by Configuring PAM</strong>
                      <span class="badge">9x fail</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_locking_out_password_attempts"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_locking_out_password_attempts"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-pam">
                    <td colspan="3" style="padding-left: 76px"><strong>Set Lockouts for Failed Password
                        Attempts</strong> <span class="badge">2x fail</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_password_pam_pwhistory_remember"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66823"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_locking_out_password_attempts"
                    data-references='{"https://public.cyber.mil/stigs/cci/":["CCI-000200"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000077-GPOS-00045"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.3.3"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm66823"
                        onclick="return openRuleDetailsDialog('idm66823')">Limit Password Reuse</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_passwords_pam_tally2"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66832"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_locking_out_password_attempts"
                    data-references='{"https://public.cyber.mil/stigs/cci/":["CCI-000044"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000021-GPOS-00005"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux":["UBTU-20-010072"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.3.2"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm66832"
                        onclick="return openRuleDetailsDialog('idm66832')">Set Deny For Failed Password Attempts</a>
                    </td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_password_quality"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_password_quality"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-pam">
                    <td colspan="3" style="padding-left: 76px"><strong>Set Password Quality Requirements</strong> <span
                        class="badge">7x fail</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_password_quality_pwquality"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_password_quality_pwquality"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_quality">
                    <td colspan="3" style="padding-left: 95px"><strong>Set Password Quality Requirements with
                        pam_pwquality</strong> <span class="badge">7x fail</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_password_pam_dcredit"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66837"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_quality_pwquality"
                    data-references='{"":["0421","0422","0431","0974","1173","1401","1504","1505","1546","1557","1558","1559","1560","1561","SRG-OS-000071-VMM-000380"],"NIST SP 800-53":["IA-5(c)","IA-5(1)(a)","CM-6(a)","IA-5(4)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R18)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-1","PR.AC-6","PR.AC-7"],"https://public.cyber.mil/stigs/cci/":["CCI-000194"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000071-GPOS-00039"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux":["UBTU-20-010052"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.3.1"],"https://www.cisecurity.org/controls/":["1","12","15","16","5"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.7","SR 1.8","SR 1.9","SR 2.1"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9","4.3.3.7.2","4.3.3.7.4"],"https://www.isaca.org/resources/cobit":["DSS05.04","DSS05.05","DSS05.07","DSS05.10","DSS06.03","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.18.1.4","A.7.1.1","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.2","A.9.4.3"],"https://www.niap-ccevs.org/Profile/PP.cfm":["FMT_MOF_EXT.1"],"PCI-DSS Requirement":["Req-8.2.3"]}'>
                    <td style="padding-left: 114px"><a href="#rule-detail-idm66837"
                        onclick="return openRuleDetailsDialog('idm66837')">Ensure PAM Enforces Password Requirements -
                        Minimum Digit Characters</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_password_pam_lcredit"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66848"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_quality_pwquality"
                    data-references='{"":["0421","0422","0431","0974","1173","1401","1504","1505","1546","1557","1558","1559","1560","1561","SRG-OS-000070-VMM-000370"],"NIST SP 800-53":["IA-5(c)","IA-5(1)(a)","CM-6(a)","IA-5(4)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R18)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-1","PR.AC-6","PR.AC-7"],"https://public.cyber.mil/stigs/cci/":["CCI-000193"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000070-GPOS-00038"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux":["UBTU-20-010051"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.3.1"],"https://www.cisecurity.org/controls/":["1","12","15","16","5"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.7","SR 1.8","SR 1.9","SR 2.1"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9","4.3.3.7.2","4.3.3.7.4"],"https://www.isaca.org/resources/cobit":["DSS05.04","DSS05.05","DSS05.07","DSS05.10","DSS06.03","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.18.1.4","A.7.1.1","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.2","A.9.4.3"],"https://www.niap-ccevs.org/Profile/PP.cfm":["FMT_MOF_EXT.1"],"PCI-DSS Requirement":["Req-8.2.3"]}'>
                    <td style="padding-left: 114px"><a href="#rule-detail-idm66848"
                        onclick="return openRuleDetailsDialog('idm66848')">Ensure PAM Enforces Password Requirements -
                        Minimum Lowercase Characters</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_password_pam_minclass"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66853"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_quality_pwquality"
                    data-references='{"":["0421","0422","0431","0974","1173","1401","1504","1505","1546","1557","1558","1559","1560","1561"],"NIST SP 800-53":["IA-5(c)","IA-5(1)(a)","CM-6(a)","IA-5(4)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-1","PR.AC-6","PR.AC-7"],"https://public.cyber.mil/stigs/cci/":["CCI-000195"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000072-GPOS-00040"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.3.1"],"https://www.cisecurity.org/controls/":["1","12","15","16","5"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.7","SR 1.8","SR 1.9","SR 2.1"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9","4.3.3.7.2","4.3.3.7.4"],"https://www.isaca.org/resources/cobit":["DSS05.04","DSS05.05","DSS05.07","DSS05.10","DSS06.03","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.18.1.4","A.7.1.1","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.2","A.9.4.3"]}'>
                    <td style="padding-left: 114px"><a href="#rule-detail-idm66853"
                        onclick="return openRuleDetailsDialog('idm66853')">Ensure PAM Enforces Password Requirements -
                        Minimum Different Categories</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_password_pam_minlen"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66858"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_quality_pwquality"
                    data-references='{"":["0421","0422","0431","0974","1173","1401","1504","1505","1546","1557","1558","1559","1560","1561","SRG-OS-000072-VMM-000390","SRG-OS-000078-VMM-000450"],"NIST SP 800-53":["IA-5(c)","IA-5(1)(a)","CM-6(a)","IA-5(4)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R18)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-1","PR.AC-6","PR.AC-7"],"https://public.cyber.mil/stigs/cci/":["CCI-000205"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000078-GPOS-00046"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux":["UBTU-20-010054"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.3.1"],"https://www.cisecurity.org/controls/":["1","12","15","16","5"],"FBI CJIS":["5.6.2.1.1"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.7","SR 1.8","SR 1.9","SR 2.1"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9","4.3.3.7.2","4.3.3.7.4"],"https://www.isaca.org/resources/cobit":["DSS05.04","DSS05.05","DSS05.07","DSS05.10","DSS06.03","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.18.1.4","A.7.1.1","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.2","A.9.4.3"],"https://www.niap-ccevs.org/Profile/PP.cfm":["FMT_MOF_EXT.1"],"PCI-DSS Requirement":["Req-8.2.3"]}'>
                    <td style="padding-left: 114px"><a href="#rule-detail-idm66858"
                        onclick="return openRuleDetailsDialog('idm66858')">Ensure PAM Enforces Password Requirements -
                        Minimum Length</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_password_pam_ocredit"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66863"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_quality_pwquality"
                    data-references='{"":["0421","0422","0431","0974","1173","1401","1504","1505","1546","1557","1558","1559","1560","1561","SRG-OS-000266-VMM-000940"],"NIST SP 800-53":["IA-5(c)","IA-5(1)(a)","CM-6(a)","IA-5(4)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R18)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-1","PR.AC-6","PR.AC-7"],"https://public.cyber.mil/stigs/cci/":["CCI-001619"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000266-GPOS-00101"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux":["UBTU-20-010055"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.3.1"],"https://www.cisecurity.org/controls/":["1","12","15","16","5"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.7","SR 1.8","SR 1.9","SR 2.1"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9","4.3.3.7.2","4.3.3.7.4"],"https://www.isaca.org/resources/cobit":["DSS05.04","DSS05.05","DSS05.07","DSS05.10","DSS06.03","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.18.1.4","A.7.1.1","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.2","A.9.4.3"],"https://www.niap-ccevs.org/Profile/PP.cfm":["FMT_MOF_EXT.1"]}'>
                    <td style="padding-left: 114px"><a href="#rule-detail-idm66863"
                        onclick="return openRuleDetailsDialog('idm66863')">Ensure PAM Enforces Password Requirements -
                        Minimum Special Characters</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_password_pam_retry"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66868"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_quality_pwquality"
                    data-references='{"NIST SP 800-53":["CM-6(a)","AC-7(a)","IA-5(4)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-1","PR.AC-6","PR.AC-7","PR.IP-1"],"https://public.cyber.mil/stigs/cci/":["CCI-000192","CCI-000366"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00225","SRG-OS-000069-GPOS-00037"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux":["UBTU-20-010057"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.3.1"],"https://www.cisecurity.org/controls/":["1","11","12","15","16","3","5","9"],"FBI CJIS":["5.5.3"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.7","SR 1.8","SR 1.9","SR 2.1","SR 7.6"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9","4.3.3.7.2","4.3.3.7.4","4.3.4.3.2","4.3.4.3.3"],"https://www.isaca.org/resources/cobit":["BAI10.01","BAI10.02","BAI10.03","BAI10.05","DSS05.04","DSS05.05","DSS05.07","DSS05.10","DSS06.03","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.12.1.2","A.12.5.1","A.12.6.2","A.14.2.2","A.14.2.3","A.14.2.4","A.18.1.4","A.7.1.1","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.2","A.9.4.3"],"https://www.niap-ccevs.org/Profile/PP.cfm":["FMT_MOF_EXT.1"]}'>
                    <td style="padding-left: 114px"><a href="#rule-detail-idm66868"
                        onclick="return openRuleDetailsDialog('idm66868')">Ensure PAM Enforces Password Requirements -
                        Authentication Retry Prompts Permitted Per-Session</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_password_pam_ucredit"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66873"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_quality_pwquality"
                    data-references='{"":["0421","0422","0431","0974","1173","1401","1504","1505","1546","1557","1558","1559","1560","1561","SRG-OS-000069-VMM-000360"],"NIST SP 800-53":["IA-5(c)","IA-5(1)(a)","CM-6(a)","IA-5(4)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R18)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-1","PR.AC-6","PR.AC-7"],"https://public.cyber.mil/stigs/cci/":["CCI-000192"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000069-GPOS-00037"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux":["UBTU-20-010050"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.3.1"],"https://www.cisecurity.org/controls/":["1","12","15","16","5"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.7","SR 1.8","SR 1.9","SR 2.1"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9","4.3.3.7.2","4.3.3.7.4"],"https://www.isaca.org/resources/cobit":["DSS05.04","DSS05.05","DSS05.07","DSS05.10","DSS06.03","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.18.1.4","A.7.1.1","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.2","A.9.4.3"],"https://www.niap-ccevs.org/Profile/PP.cfm":["FMT_MOF_EXT.1"],"PCI-DSS Requirement":["Req-8.2.3"]}'>
                    <td style="padding-left: 114px"><a href="#rule-detail-idm66873"
                        onclick="return openRuleDetailsDialog('idm66873')">Ensure PAM Enforces Password Requirements -
                        Minimum Uppercase Characters</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_accounts-restrictions"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_accounts-restrictions"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts">
                    <td colspan="3" style="padding-left: 57px"><strong>Protect Accounts by Restricting Password-Based
                        Login</strong> <span class="badge">6x fail</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_account_expiration"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_account_expiration"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-restrictions">
                    <td colspan="3" style="padding-left: 76px"><strong>Set Account Expiration Parameters</strong> <span
                        class="badge">1x fail</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_account_disable_post_pw_expiration"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66900"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_account_expiration"
                    data-references='{"":["SRG-OS-000003-VMM-000030","SRG-OS-000118-VMM-000590"],"NIST SP 800-171":["3.5.6"],"NIST SP 800-53":["IA-4(e)","AC-2(3)","CM-6(a)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["DE.CM-1","DE.CM-3","PR.AC-1","PR.AC-4","PR.AC-6","PR.AC-7"],"https://public.cyber.mil/stigs/cci/":["CCI-000017","CCI-000795"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000118-GPOS-00060"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux":["UBTU-20-010409"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.4.1.4"],"https://www.cisecurity.org/controls/":["1","12","13","14","15","16","18","3","5","7","8"],"FBI CJIS":["5.6.2.1.1"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.7","SR 1.8","SR 1.9","SR 2.1","SR 6.2"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9","4.3.3.7.2","4.3.3.7.3","4.3.3.7.4"],"https://www.isaca.org/resources/cobit":["DSS01.03","DSS03.05","DSS05.04","DSS05.05","DSS05.07","DSS05.10","DSS06.03","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.12.4.1","A.12.4.3","A.18.1.4","A.6.1.2","A.7.1.1","A.9.1.2","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.1","A.9.4.2","A.9.4.3","A.9.4.4","A.9.4.5"],"https://www.nerc.com/pa/Stand/Standard%20Purpose%20Statement%20DL/US_Standard_One-Stop-Shop.xlsx":["CIP-004-6 R2.2.2","CIP-004-6 R2.2.3","CIP-007-3 R.1.3","CIP-007-3 R5","CIP-007-3 R5.1.1","CIP-007-3 R5.1.3","CIP-007-3 R5.2.1","CIP-007-3 R5.2.3"],"PCI-DSS Requirement":["Req-8.1.4"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm66900"
                        onclick="return openRuleDetailsDialog('idm66900')">Set Account Expiration Following
                        Inactivity</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_password_expiration"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_password_expiration"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-restrictions">
                    <td colspan="3" style="padding-left: 76px"><strong>Set Password Expiration Parameters</strong> <span
                        class="badge">4x fail</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_maximum_age_login_defs"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66913"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_expiration"
                    data-references='{"":["0418","1055","1402"],"NIST SP 800-171":["3.5.6"],"NIST SP 800-53":["IA-5(f)","IA-5(1)(d)","CM-6(a)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R18)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-1","PR.AC-6","PR.AC-7"],"https://public.cyber.mil/stigs/cci/":["CCI-000199"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000076-GPOS-00044"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux":["UBTU-20-010008"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.4.1.1"],"https://www.cisecurity.org/controls/":["1","12","15","16","5"],"FBI CJIS":["5.6.2.1"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.7","SR 1.8","SR 1.9","SR 2.1"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9","4.3.3.7.2","4.3.3.7.4"],"https://www.isaca.org/resources/cobit":["DSS05.04","DSS05.05","DSS05.07","DSS05.10","DSS06.03","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.18.1.4","A.7.1.1","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.2","A.9.4.3"],"PCI-DSS Requirement":["Req-8.2.4"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm66913"
                        onclick="return openRuleDetailsDialog('idm66913')">Set Password Maximum Age</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_minimum_age_login_defs"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66918"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_expiration"
                    data-references='{"":["0418","1055","1402"],"NIST SP 800-171":["3.5.8"],"NIST SP 800-53":["IA-5(f)","IA-5(1)(d)","CM-6(a)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-1","PR.AC-6","PR.AC-7"],"https://public.cyber.mil/stigs/cci/":["CCI-000198"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000075-GPOS-00043"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux":["UBTU-20-010007"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.4.1.2"],"https://www.cisecurity.org/controls/":["1","12","15","16","5"],"FBI CJIS":["5.6.2.1.1"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.7","SR 1.8","SR 1.9","SR 2.1"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9","4.3.3.7.2","4.3.3.7.4"],"https://www.isaca.org/resources/cobit":["DSS05.04","DSS05.05","DSS05.07","DSS05.10","DSS06.03","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.18.1.4","A.7.1.1","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.2","A.9.4.3"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm66918"
                        onclick="return openRuleDetailsDialog('idm66918')">Set Password Minimum Age</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_password_set_max_life_existing"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66925"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_expiration"
                    data-references='{"":["SRG-OS-000076-VMM-000430"],"NIST SP 800-53":["IA-5(f)","IA-5(1)(d)","CM-6(a)"],"https://public.cyber.mil/stigs/cci/":["CCI-000199"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000076-GPOS-00044"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.4.1.1"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm66925"
                        onclick="return openRuleDetailsDialog('idm66925')">Set Existing Passwords Maximum Age</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_password_set_min_life_existing"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66931"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_expiration"
                    data-references='{"":["SRG-OS-000075-VMM000420"],"NIST SP 800-53":["IA-5(f)","IA-5(1)(d)","CM-6(a)"],"https://public.cyber.mil/stigs/cci/":["CCI-000198"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000075-GPOS-00043"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.4.1.2"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm66931"
                        onclick="return openRuleDetailsDialog('idm66931')">Set Existing Passwords Minimum Age</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_password_warn_age_login_defs"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_accounts_password_warn_age_login_defs"
                    id="rule-overview-leaf-idm66937"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_expiration"
                    data-references='{"":["0418","1055","1402"],"NIST SP 800-171":["3.5.8"],"NIST SP 800-53":["IA-5(f)","IA-5(1)(d)","CM-6(a)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["DE.CM-1","DE.CM-3","PR.AC-1","PR.AC-4","PR.AC-6","PR.AC-7"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.4.1.3"],"https://www.cisecurity.org/controls/":["1","12","13","14","15","16","18","3","5","7","8"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.7","SR 1.8","SR 1.9","SR 2.1","SR 6.2"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9","4.3.3.7.2","4.3.3.7.3","4.3.3.7.4"],"https://www.isaca.org/resources/cobit":["DSS01.03","DSS03.05","DSS05.04","DSS05.05","DSS05.07","DSS05.10","DSS06.03","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.12.4.1","A.12.4.3","A.18.1.4","A.6.1.2","A.7.1.1","A.9.1.2","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.1","A.9.4.2","A.9.4.3","A.9.4.4","A.9.4.5"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm66937"
                        onclick="return openRuleDetailsDialog('idm66937')">Set Password Warning Age</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_password_storage"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_password_storage"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-restrictions">
                    <td colspan="3" style="padding-left: 76px">Verify Proper Storage and Existence of Password
                      Hashes
                      <script>$(document).ready(function () { $('.treetable').treetable("collapseNode", "xccdf_org.ssgproject.content_group_password_storage"); });</script>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_password_all_shadowed_sha512"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_accounts_password_all_shadowed_sha512"
                    id="rule-overview-leaf-idm66944"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_storage"
                    data-references='{"NIST SP 800-53":["IA-5(1)(c)","IA-5(1).1(v)","IA-7","IA-7.1"],"https://public.cyber.mil/stigs/cci/":["CCI-000196","CCI-000803"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000073-GPOS-00041","SRG-OS-000120-GPOS-00061"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.3.4"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm66944"
                        onclick="return openRuleDetailsDialog('idm66944')">Verify All Account Password Hashes are
                        Shadowed with SHA512</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_no_empty_passwords"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_no_empty_passwords"
                    id="rule-overview-leaf-idm66954"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_storage"
                    data-references='{"NIST SP 800-171":["3.1.1","3.1.5"],"NIST SP 800-53":["IA-5(1)(a)","IA-5(c)","CM-6(a)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-1","PR.AC-4","PR.AC-6","PR.AC-7","PR.DS-5"],"https://public.cyber.mil/stigs/cci/":["CCI-000366"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00227"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["6.2.1"],"https://www.cisecurity.org/controls/":["1","12","13","14","15","16","18","3","5"],"FBI CJIS":["5.5.2"],"https://www.gpo.gov/fdsys/pkg/CFR-2007-title45-vol1/pdf/CFR-2007-title45-vol1-chapA-subchapC.pdf":["164.308(a)(1)(ii)(B)","164.308(a)(7)(i)","164.308(a)(7)(ii)(A)","164.310(a)(1)","164.310(a)(2)(i)","164.310(a)(2)(ii)","164.310(a)(2)(iii)","164.310(b)","164.310(c)","164.310(d)(1)","164.310(d)(2)(iii)"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.7","SR 1.8","SR 1.9","SR 2.1","SR 5.2"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9","4.3.3.7.2","4.3.3.7.3","4.3.3.7.4"],"https://www.isaca.org/resources/cobit":["APO01.06","DSS05.04","DSS05.05","DSS05.07","DSS05.10","DSS06.02","DSS06.03","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.10.1.1","A.11.1.4","A.11.1.5","A.11.2.1","A.13.1.1","A.13.1.3","A.13.2.1","A.13.2.3","A.13.2.4","A.14.1.2","A.14.1.3","A.18.1.4","A.6.1.2","A.7.1.1","A.7.1.2","A.7.3.1","A.8.2.2","A.8.2.3","A.9.1.1","A.9.1.2","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.1","A.9.4.2","A.9.4.3","A.9.4.4","A.9.4.5"],"https://www.niap-ccevs.org/Profile/PP.cfm":["FIA_UAU.1"],"PCI-DSS Requirement":["Req-8.2.3"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm66954"
                        onclick="return openRuleDetailsDialog('idm66954')">Prevent Login to Accounts With Empty
                        Password</a></td>
                    <td class="rule-severity" style="text-align: center">high</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_no_netrc_files"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_no_netrc_files"
                    id="rule-overview-leaf-idm66960"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_password_storage"
                    data-references='{"NIST SP 800-53":["IA-5(h)","IA-5(1)(c)","CM-6(a)","IA-5(7)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-1","PR.AC-4","PR.AC-6","PR.AC-7","PR.PT-3"],"https://public.cyber.mil/stigs/cci/":["CCI-000196"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["6.2.9"],"https://www.cisecurity.org/controls/":["1","11","12","14","15","16","18","3","5"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.11","SR 1.12","SR 1.13","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.6","SR 1.7","SR 1.8","SR 1.9","SR 2.1","SR 2.2","SR 2.3","SR 2.4","SR 2.5","SR 2.6","SR 2.7"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.5.3","4.3.3.5.4","4.3.3.5.5","4.3.3.5.6","4.3.3.5.7","4.3.3.5.8","4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9","4.3.3.7.1","4.3.3.7.2","4.3.3.7.3","4.3.3.7.4"],"https://www.isaca.org/resources/cobit":["DSS05.02","DSS05.04","DSS05.05","DSS05.07","DSS05.10","DSS06.03","DSS06.06","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.18.1.4","A.6.1.2","A.7.1.1","A.9.1.2","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.1","A.9.4.2","A.9.4.3","A.9.4.4","A.9.4.5"],"https://www.nerc.com/pa/Stand/Standard%20Purpose%20Statement%20DL/US_Standard_One-Stop-Shop.xlsx":["CIP-003-8 R1.3","CIP-003-8 R3","CIP-003-8 R3.1","CIP-003-8 R3.2","CIP-003-8 R3.3","CIP-003-8 R5.1.1","CIP-003-8 R5.3","CIP-004-6 R2.2.3","CIP-004-6 R2.3","CIP-007-3 R5.1","CIP-007-3 R5.1.2","CIP-007-3 R5.2","CIP-007-3 R5.3.1","CIP-007-3 R5.3.2","CIP-007-3 R5.3.3"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm66960"
                        onclick="return openRuleDetailsDialog('idm66960')">Verify No netrc Files Exist</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_root_logins"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_root_logins"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-restrictions">
                    <td colspan="3" style="padding-left: 76px"><strong>Restrict Root Logins</strong> <span
                        class="badge">1x fail</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_no_uid_except_zero"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_accounts_no_uid_except_zero"
                    id="rule-overview-leaf-idm66964" data-tt-parent-id="xccdf_org.ssgproject.content_group_root_logins"
                    data-references='{"NIST SP 800-171":["3.1.1","3.1.5"],"NIST SP 800-53":["IA-2","AC-6(5)","IA-4(b)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-1","PR.AC-4","PR.AC-6","PR.AC-7","PR.DS-5"],"https://public.cyber.mil/stigs/cci/":["CCI-000366"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00227"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["6.2.2"],"https://www.cisecurity.org/controls/":["1","12","13","14","15","16","18","3","5"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.7","SR 1.8","SR 1.9","SR 2.1","SR 5.2"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9","4.3.3.7.2","4.3.3.7.3","4.3.3.7.4"],"https://www.isaca.org/resources/cobit":["APO01.06","DSS05.04","DSS05.05","DSS05.07","DSS05.10","DSS06.02","DSS06.03","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.10.1.1","A.11.1.4","A.11.1.5","A.11.2.1","A.13.1.1","A.13.1.3","A.13.2.1","A.13.2.3","A.13.2.4","A.14.1.2","A.14.1.3","A.18.1.4","A.6.1.2","A.7.1.1","A.7.1.2","A.7.3.1","A.8.2.2","A.8.2.3","A.9.1.1","A.9.1.2","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.1","A.9.4.2","A.9.4.3","A.9.4.4","A.9.4.5"],"https://www.nerc.com/pa/Stand/Standard%20Purpose%20Statement%20DL/US_Standard_One-Stop-Shop.xlsx":["CIP-003-8 R5.1.1","CIP-003-8 R5.3","CIP-004-6 R2.2.3","CIP-004-6 R2.3","CIP-007-3 R5.1","CIP-007-3 R5.1.2","CIP-007-3 R5.2","CIP-007-3 R5.3.1","CIP-007-3 R5.3.2","CIP-007-3 R5.3.3"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm66964"
                        onclick="return openRuleDetailsDialog('idm66964')">Verify Only Root Has UID 0</a></td>
                    <td class="rule-severity" style="text-align: center">high</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_no_shelllogin_for_systemaccounts"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_no_shelllogin_for_systemaccounts"
                    id="rule-overview-leaf-idm66974" data-tt-parent-id="xccdf_org.ssgproject.content_group_root_logins"
                    data-references='{"":["1491"],"NIST SP 800-53":["AC-6","CM-6(a)","CM-6(b)","CM-6.1(iv)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["DE.CM-1","DE.CM-3","PR.AC-1","PR.AC-4","PR.AC-6"],"https://public.cyber.mil/stigs/cci/":["CCI-000366"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00227"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.4.2"],"https://www.cisecurity.org/controls/":["1","12","13","14","15","16","18","3","5","7","8"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.2","SR 1.3","SR 1.4","SR 1.5","SR 1.7","SR 1.8","SR 1.9","SR 2.1","SR 6.2"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.2.2","4.3.3.5.1","4.3.3.5.2","4.3.3.7.2","4.3.3.7.3","4.3.3.7.4"],"https://www.isaca.org/resources/cobit":["DSS01.03","DSS03.05","DSS05.04","DSS05.05","DSS05.07","DSS06.03"],"https://www.iso.org/standard/54534.html":["A.12.4.1","A.12.4.3","A.6.1.2","A.7.1.1","A.9.1.2","A.9.2.1","A.9.2.2","A.9.2.3","A.9.2.4","A.9.2.6","A.9.3.1","A.9.4.1","A.9.4.2","A.9.4.3","A.9.4.4","A.9.4.5"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm66974"
                        onclick="return openRuleDetailsDialog('idm66974')">Ensure that System Accounts Do Not Run a
                        Shell Upon Login</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_use_pam_wheel_for_su"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66984" data-tt-parent-id="xccdf_org.ssgproject.content_group_root_logins"
                    data-references='{"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000373-GPOS-00156","SRG-OS-000312-GPOS-00123"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.6"],"https://www.niap-ccevs.org/Profile/PP.cfm":["FMT_SMF_EXT.1.1"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm66984"
                        onclick="return openRuleDetailsDialog('idm66984')">Enforce usage of pam_wheel for su
                        authentication</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_accounts-session"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_accounts-session"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts">
                    <td colspan="3" style="padding-left: 57px"><strong>Secure Session Configuration Files for Login
                        Accounts</strong> <span class="badge">6x fail</span> <span class="badge">1x error</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_root_paths"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_root_paths"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-session">
                    <td colspan="3" style="padding-left: 76px">Ensure that No Dangerous Directories Exist in Root's Path
                      <script>$(document).ready(function () { $('.treetable').treetable("collapseNode", "xccdf_org.ssgproject.content_group_root_paths"); });</script>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_root_path_dirs_no_write"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_accounts_root_path_dirs_no_write"
                    id="rule-overview-leaf-idm67021" data-tt-parent-id="xccdf_org.ssgproject.content_group_root_paths"
                    data-references='{"NIST SP 800-53":["CM-6(a)","CM-6(a)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.IP-1"],"https://public.cyber.mil/stigs/cci/":["CCI-000366"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["6.2.3"],"https://www.cisecurity.org/controls/":["11","3","9"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 7.6"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.4.3.2","4.3.4.3.3"],"https://www.isaca.org/resources/cobit":["BAI10.01","BAI10.02","BAI10.03","BAI10.05"],"https://www.iso.org/standard/54534.html":["A.12.1.2","A.12.5.1","A.12.6.2","A.14.2.2","A.14.2.3","A.14.2.4"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm67021"
                        onclick="return openRuleDetailsDialog('idm67021')">Ensure that Root's Path Does Not Include
                        World or Group-Writable Directories</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_user_umask"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_user_umask"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-session">
                    <td colspan="3" style="padding-left: 76px"><strong>Ensure that Users Have Sensible Umask
                        Values</strong> <span class="badge">4x fail</span> <span class="badge">1x error</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_umask_etc_bashrc"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm67027" data-tt-parent-id="xccdf_org.ssgproject.content_group_user_umask"
                    data-references='{"NIST SP 800-53":["AC-6(1)","CM-6(a)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R35)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.IP-2"],"https://public.cyber.mil/stigs/cci/":["CCI-000366"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00228","SRG-OS-000480-GPOS-00227"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.4.4"],"https://www.cisecurity.org/controls/":["18"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.4.3.3"],"https://www.isaca.org/resources/cobit":["APO13.01","BAI03.01","BAI03.02","BAI03.03"],"https://www.iso.org/standard/54534.html":["A.14.1.1","A.14.2.1","A.14.2.5","A.6.1.5"],"https://www.nerc.com/pa/Stand/Standard%20Purpose%20Statement%20DL/US_Standard_One-Stop-Shop.xlsx":["CIP-003-8 R5.1.1","CIP-003-8 R5.3","CIP-004-6 R2.3","CIP-007-3 R2.1","CIP-007-3 R2.2","CIP-007-3 R2.3","CIP-007-3 R5.1","CIP-007-3 R5.1.1","CIP-007-3 R5.1.2"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm67027"
                        onclick="return openRuleDetailsDialog('idm67027')">Ensure the Default Bash Umask is Set
                        Correctly</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_umask_etc_csh_cshrc"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm67032" data-tt-parent-id="xccdf_org.ssgproject.content_group_user_umask"
                    data-references='{"NIST SP 800-53":["AC-6(1)","CM-6(a)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.IP-2"],"https://public.cyber.mil/stigs/cci/":["CCI-000366"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00228","SRG-OS-000480-GPOS-00227"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.4.4"],"https://www.cisecurity.org/controls/":["18"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.4.3.3"],"https://www.isaca.org/resources/cobit":["APO13.01","BAI03.01","BAI03.02","BAI03.03"],"https://www.iso.org/standard/54534.html":["A.14.1.1","A.14.2.1","A.14.2.5","A.6.1.5"],"https://www.nerc.com/pa/Stand/Standard%20Purpose%20Statement%20DL/US_Standard_One-Stop-Shop.xlsx":["CIP-003-8 R5.1.1","CIP-003-8 R5.3","CIP-004-6 R2.3","CIP-007-3 R2.1","CIP-007-3 R2.2","CIP-007-3 R2.3","CIP-007-3 R5.1","CIP-007-3 R5.1.1","CIP-007-3 R5.1.2"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm67032"
                        onclick="return openRuleDetailsDialog('idm67032')">Ensure the Default C Shell Umask is Set
                        Correctly</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_umask_etc_login_defs"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm67037" data-tt-parent-id="xccdf_org.ssgproject.content_group_user_umask"
                    data-references='{"NIST SP 800-53":["AC-6(1)","CM-6(a)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R35)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.IP-1","PR.IP-2"],"https://public.cyber.mil/stigs/cci/":["CCI-000366"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00228"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux":["UBTU-20-010016"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.4.4"],"https://www.cisecurity.org/controls/":["11","18","3","9"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 7.6"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.4.3.2","4.3.4.3.3"],"https://www.isaca.org/resources/cobit":["APO13.01","BAI03.01","BAI03.02","BAI03.03","BAI10.01","BAI10.02","BAI10.03","BAI10.05"],"https://www.iso.org/standard/54534.html":["A.12.1.2","A.12.5.1","A.12.6.2","A.14.1.1","A.14.2.1","A.14.2.2","A.14.2.3","A.14.2.4","A.14.2.5","A.6.1.5"],"https://www.nerc.com/pa/Stand/Standard%20Purpose%20Statement%20DL/US_Standard_One-Stop-Shop.xlsx":["CIP-003-8 R5.1.1","CIP-003-8 R5.3","CIP-004-6 R2.3","CIP-007-3 R2.1","CIP-007-3 R2.2","CIP-007-3 R2.3","CIP-007-3 R5.1","CIP-007-3 R5.1.1","CIP-007-3 R5.1.2"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm67037"
                        onclick="return openRuleDetailsDialog('idm67037')">Ensure the Default Umask is Set Correctly in
                        login.defs</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_umask_etc_profile"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm67042" data-tt-parent-id="xccdf_org.ssgproject.content_group_user_umask"
                    data-references='{"NIST SP 800-53":["AC-6(1)","CM-6(a)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R35)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.IP-2"],"https://public.cyber.mil/stigs/cci/":["CCI-000366"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00228","SRG-OS-000480-GPOS-00227"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.4.4"],"https://www.cisecurity.org/controls/":["18"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.4.3.3"],"https://www.isaca.org/resources/cobit":["APO13.01","BAI03.01","BAI03.02","BAI03.03"],"https://www.iso.org/standard/54534.html":["A.14.1.1","A.14.2.1","A.14.2.5","A.6.1.5"],"https://www.nerc.com/pa/Stand/Standard%20Purpose%20Statement%20DL/US_Standard_One-Stop-Shop.xlsx":["CIP-003-8 R5.1.1","CIP-003-8 R5.3","CIP-004-6 R2.3","CIP-007-3 R2.1","CIP-007-3 R2.2","CIP-007-3 R2.3","CIP-007-3 R5.1","CIP-007-3 R5.1.1","CIP-007-3 R5.1.2"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm67042"
                        onclick="return openRuleDetailsDialog('idm67042')">Ensure the Default Umask is Set Correctly in
                        /etc/profile</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_umask_interactive_users"
                    class="rule-overview-leaf rule-overview-leaf-error rule-overview-needs-attention"
                    id="rule-overview-leaf-idm67047" data-tt-parent-id="xccdf_org.ssgproject.content_group_user_umask"
                    data-references='{"https://public.cyber.mil/stigs/cci/":["CCI-000366","CCI-001814"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00227"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.4.4"]}'>
                    <td style="padding-left: 95px"><a href="#rule-detail-idm67047"
                        onclick="return openRuleDetailsDialog('idm67047')">Ensure the Default Umask is Set Correctly For
                        Interactive Users</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-error">
                      <div><abbr
                          title="The checking engine could not complete the evaluation, therefore the status of the target's compliance with the rule is not certain. This could happen, for example, if a testing tool was run with insufficient privileges and could not gather all of the necessary information.">error</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_tmout"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm66996"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-session"
                    data-references='{"":["SRG-OS-000163-VMM-000700","SRG-OS-000279-VMM-001010"],"NIST SP 800-171":["3.1.11"],"NIST SP 800-53":["AC-12","SC-10","AC-2(5)","CM-6(a)"],"http://www.ssi.gouv.fr/administration/bonnes-pratiques/":["BP28(R29)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-7"],"https://public.cyber.mil/stigs/cci/":["CCI-000057","CCI-001133","CCI-002361"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000163-GPOS-00072","SRG-OS-000029-GPOS-00010"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux":["UBTU-20-010013"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["5.4.5"],"https://www.cisecurity.org/controls/":["1","12","15","16"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 1.1","SR 1.10","SR 1.2","SR 1.5","SR 1.7","SR 1.8","SR 1.9"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.6.1","4.3.3.6.2","4.3.3.6.3","4.3.3.6.4","4.3.3.6.5","4.3.3.6.6","4.3.3.6.7","4.3.3.6.8","4.3.3.6.9"],"https://www.isaca.org/resources/cobit":["DSS05.04","DSS05.10","DSS06.10"],"https://www.iso.org/standard/54534.html":["A.18.1.4","A.9.2.1","A.9.2.4","A.9.3.1","A.9.4.2","A.9.4.3"],"https://www.nerc.com/pa/Stand/Standard%20Purpose%20Statement%20DL/US_Standard_One-Stop-Shop.xlsx":["CIP-004-6 R2.2.3","CIP-007-3 R5.1","CIP-007-3 R5.2","CIP-007-3 R5.3.1","CIP-007-3 R5.3.2","CIP-007-3 R5.3.3"],"https://www.niap-ccevs.org/Profile/PP.cfm":["FMT_MOF_EXT.1"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm66996"
                        onclick="return openRuleDetailsDialog('idm66996')">Set Interactive Session Timeout</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_user_dot_group_ownership"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_accounts_user_dot_group_ownership"
                    id="rule-overview-leaf-idm67001"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-session"
                    data-references='{"https://public.cyber.mil/stigs/cci/":["CCI-000366"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00227"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["6.2.7"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm67001"
                        onclick="return openRuleDetailsDialog('idm67001')">User Initialization Files Must Be Group-Owned
                        By The Primary User</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_user_dot_user_ownership"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_accounts_user_dot_user_ownership"
                    id="rule-overview-leaf-idm67005"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-session"
                    data-references='{"https://public.cyber.mil/stigs/cci/":["CCI-000366"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00227"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["6.2.7"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm67005"
                        onclick="return openRuleDetailsDialog('idm67005')">User Initialization Files Must Be Owned By
                        the Primary User</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_accounts_user_interactive_home_directory_exists"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_accounts_user_interactive_home_directory_exists"
                    id="rule-overview-leaf-idm67009"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-session"
                    data-references='{"https://public.cyber.mil/stigs/cci/":["CCI-000366"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00227"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["6.2.4"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm67009"
                        onclick="return openRuleDetailsDialog('idm67009')">All Interactive Users Home Directories Must
                        Exist</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_file_permissions_home_directories"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm67015"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_accounts-session"
                    data-references='{"https://public.cyber.mil/stigs/cci/":["CCI-000366"],"https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cgeneral-purpose-os":["SRG-OS-000480-GPOS-00227"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["6.2.5"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm67015"
                        onclick="return openRuleDetailsDialog('idm67015')">All Interactive User Home Directories Must
                        Have mode 0750 Or Less Permissive</a></td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_bootloader-grub2"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_bootloader-grub2"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_system">
                    <td colspan="3" style="padding-left: 38px"><strong>GRUB2 bootloader configuration</strong> <span
                        class="badge">2x fail</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_group_non-uefi"
                    class="rule-overview-inner-node rule-overview-inner-node-id-xccdf_org.ssgproject.content_group_non-uefi"
                    data-tt-parent-id="xccdf_org.ssgproject.content_group_bootloader-grub2">
                    <td colspan="3" style="padding-left: 57px"><strong>Non-UEFI GRUB2 bootloader configuration</strong>
                      <span class="badge">2x fail</span></td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_file_owner_grub2_cfg"
                    class="rule-overview-leaf rule-overview-leaf-pass rule-overview-leaf-id-xccdf_org.ssgproject.content_rule_file_owner_grub2_cfg"
                    id="rule-overview-leaf-idm67303" data-tt-parent-id="xccdf_org.ssgproject.content_group_non-uefi"
                    data-references='{"NIST SP 800-171":["3.4.5"],"NIST SP 800-53":["CM-6(a)","AC-6(1)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-4","PR.DS-5"],"https://public.cyber.mil/stigs/cci/":["CCI-000225"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.5.2"],"https://www.cisecurity.org/controls/":["12","13","14","15","16","18","3","5"],"FBI CJIS":["5.5.2.2"],"https://www.gpo.gov/fdsys/pkg/CFR-2007-title45-vol1/pdf/CFR-2007-title45-vol1-chapA-subchapC.pdf":["164.308(a)(1)(ii)(B)","164.308(a)(7)(i)","164.308(a)(7)(ii)(A)","164.310(a)(1)","164.310(a)(2)(i)","164.310(a)(2)(ii)","164.310(a)(2)(iii)","164.310(b)","164.310(c)","164.310(d)(1)","164.310(d)(2)(iii)"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 2.1","SR 5.2"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.7.3"],"https://www.isaca.org/resources/cobit":["APO01.06","DSS05.04","DSS05.07","DSS06.02"],"https://www.iso.org/standard/54534.html":["A.10.1.1","A.11.1.4","A.11.1.5","A.11.2.1","A.13.1.1","A.13.1.3","A.13.2.1","A.13.2.3","A.13.2.4","A.14.1.2","A.14.1.3","A.6.1.2","A.7.1.1","A.7.1.2","A.7.3.1","A.8.2.2","A.8.2.3","A.9.1.1","A.9.1.2","A.9.2.3","A.9.4.1","A.9.4.4","A.9.4.5"],"PCI-DSS Requirement":["Req-7.1"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm67303"
                        onclick="return openRuleDetailsDialog('idm67303')">Verify /boot/grub/grub.cfg User Ownership</a>
                    </td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-pass">
                      <div><abbr
                          title="The target system or system component satisfied all the conditions of the rule.">pass</abbr>
                      </div>
                    </td>
                  </tr>
                  <tr data-tt-id="xccdf_org.ssgproject.content_rule_file_permissions_grub2_cfg"
                    class="rule-overview-leaf rule-overview-leaf-fail rule-overview-needs-attention"
                    id="rule-overview-leaf-idm67307" data-tt-parent-id="xccdf_org.ssgproject.content_group_non-uefi"
                    data-references='{"NIST SP 800-171":["3.4.5"],"NIST SP 800-53":["CM-6(a)","AC-6(1)"],"https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04162018.pdf":["PR.AC-4","PR.DS-5"],"https://public.cyber.mil/stigs/cci/":["CCI-000225"],"https://www.cisecurity.org/benchmark/ubuntu_linux/":["1.5.2"],"https://www.cisecurity.org/controls/":["12","13","14","15","16","18","3","5"],"https://www.gpo.gov/fdsys/pkg/CFR-2007-title45-vol1/pdf/CFR-2007-title45-vol1-chapA-subchapC.pdf":["164.308(a)(1)(ii)(B)","164.308(a)(7)(i)","164.308(a)(7)(ii)(A)","164.310(a)(1)","164.310(a)(2)(i)","164.310(a)(2)(ii)","164.310(a)(2)(iii)","164.310(b)","164.310(c)","164.310(d)(1)","164.310(d)(2)(iii)"],"https://www.isa.org/products/ansi-isa-62443-3-3-99-03-03-2013-security-for-indu":["SR 2.1","SR 5.2"],"https://www.isa.org/products/isa-62443-2-1-2009-security-for-industrial-automat":["4.3.3.7.3"],"https://www.isaca.org/resources/cobit":["APO01.06","DSS05.04","DSS05.07","DSS06.02"],"https://www.iso.org/standard/54534.html":["A.10.1.1","A.11.1.4","A.11.1.5","A.11.2.1","A.13.1.1","A.13.1.3","A.13.2.1","A.13.2.3","A.13.2.4","A.14.1.2","A.14.1.3","A.6.1.2","A.7.1.1","A.7.1.2","A.7.3.1","A.8.2.2","A.8.2.3","A.9.1.1","A.9.1.2","A.9.2.3","A.9.4.1","A.9.4.4","A.9.4.5"]}'>
                    <td style="padding-left: 76px"><a href="#rule-detail-idm67307"
                        onclick="return openRuleDetailsDialog('idm67307')">Verify /boot/grub/grub.cfg Permissions</a>
                    </td>
                    <td class="rule-severity" style="text-align: center">medium</td>
                    <td class="rule-result rule-result-fail">
                      <div><abbr
                          title="The target system or system component did not satisfy at least one condition of the rule.">fail</abbr>
                      </div>
                    </td>
                  </tr>
    </div>
</foreignObject>
</svg>


![CI/CD Pipeline](https://github.com/juice-shop/juice-shop/workflows/CI/CD%20Pipeline/badge.svg?branch=master)
[![Test Coverage](https://api.codeclimate.com/v1/badges/6206c8f3972bcc97a033/test_coverage)](https://codeclimate.com/github/juice-shop/juice-shop/test_coverage)
[![Maintainability](https://api.codeclimate.com/v1/badges/6206c8f3972bcc97a033/maintainability)](https://codeclimate.com/github/juice-shop/juice-shop/maintainability)
[![Code Climate technical debt](https://img.shields.io/codeclimate/tech-debt/juice-shop/juice-shop)](https://codeclimate.com/github/juice-shop/juice-shop/trends/technical_debt)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/223/badge)](https://bestpractices.coreinfrastructure.org/projects/223)
![GitHub stars](https://img.shields.io/github/stars/juice-shop/juice-shop.svg?label=GitHub%20%E2%98%85&style=flat)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](CODE_OF_CONDUCT.md)

> [The most trustworthy online shop out there.](https://twitter.com/dschadow/status/706781693504589824)
> ([@dschadow](https://github.com/dschadow)) —
> [The best juice shop on the whole internet!](https://twitter.com/shehackspurple/status/907335357775085568)
> ([@shehackspurple](https://twitter.com/shehackspurple)) —
> [Actually the most bug-free vulnerable application in existence!](https://youtu.be/TXAztSpYpvE?t=26m35s)
> ([@vanderaj](https://twitter.com/vanderaj)) —
> [First you 😂😂then you 😢](https://twitter.com/kramse/status/1073168529405472768)
> ([@kramse](https://twitter.com/kramse)) —
> [But this doesn't have anything to do with juice.](https://twitter.com/coderPatros/status/1199268774626488320)
> ([@coderPatros' wife](https://twitter.com/coderPatros))

OWASP Juice Shop is probably the most modern and sophisticated insecure web application! It can be used in security
trainings, awareness demos, CTFs and as a guinea pig for security tools! Juice Shop encompasses vulnerabilities from the
entire
[OWASP Top Ten](https://owasp.org/www-project-top-ten) along with many other security flaws found in real-world
applications!

![Juice Shop Screenshot Slideshow](screenshots/slideshow.gif)

For a detailed introduction, full list of features and architecture overview please visit the official project page:
<https://owasp-juice.shop>

## Table of contents

- [Setup](#setup)
    - [Deploy on Heroku (free ($0/month) dyno)](#deploy-on-heroku-free-0month-dyno)
    - [From Sources](#from-sources)
    - [Packaged Distributions](#packaged-distributions)
    - [Docker Container](#docker-container)
    - [Vagrant](#vagrant)
    - [Amazon EC2 Instance](#amazon-ec2-instance)
    - [Azure Container Instance](#azure-container-instance)
    - [Google Compute Engine Instance](#google-compute-engine-instance)
- [Demo](#demo)
- [Documentation](#documentation)
    - [Node.js version compatibility](#nodejs-version-compatibility)
    - [Troubleshooting](#troubleshooting)
    - [Official companion guide](#official-companion-guide)
- [Contributing](#contributing)
- [References](#references)
- [Merchandise](#merchandise)
- [Donations](#donations)
- [Contributors](#contributors)
- [Licensing](#licensing)

## Setup

> You can find some less common installation variations in
> [the _Running OWASP Juice Shop_ documentation](https://pwning.owasp-juice.shop/part1/running.html).

### Deploy on Heroku (free ($0/month) dyno)

1. [Sign up to Heroku](https://signup.heroku.com/) and
   [log in to your account](https://id.heroku.com/login)
2. Click the button below and follow the instructions

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

> This is the quickest way to get a running instance of Juice Shop! If
> you have forked this repository, the deploy button will automatically
> pick up your fork for deployment! As long as you do not perform any
> DDoS attacks you are free to use any tools or scripts to hack your
> Juice Shop instance on Heroku!

### From Sources

![GitHub repo size](https://img.shields.io/github/repo-size/juice-shop/juice-shop.svg)

1. Install [node.js](#nodejs-version-compatibility)
2. Run `git clone https://github.com/juice-shop/juice-shop.git --depth 1` (or
   clone [your own fork](https://github.com/juice-shop/juice-shop/fork)
   of the repository)
3. Go into the cloned folder with `cd juice-shop`
4. Run `npm install` (only has to be done before first start or when you change the source code)
5. Run `npm start`
6. Browse to <http://localhost:3000>

### Packaged Distributions

[![GitHub release](https://img.shields.io/github/downloads/juice-shop/juice-shop/total.svg)](https://github.com/juice-shop/juice-shop/releases/latest)
[![SourceForge](https://img.shields.io/sourceforge/dm/juice-shop?label=sourceforge%20downloads)](https://sourceforge.net/projects/juice-shop/)
[![SourceForge](https://img.shields.io/sourceforge/dt/juice-shop?label=sourceforge%20downloads)](https://sourceforge.net/projects/juice-shop/)

1. Install a 64bit [node.js](#nodejs-version-compatibility) on your Windows, MacOS or Linux machine
2. Download `juice-shop-<version>_<node-version>_<os>_x64.zip` (or
   `.tgz`) attached to
   [latest release](https://github.com/juice-shop/juice-shop/releases/latest)
3. Unpack and `cd` into the unpacked folder
4. Run `npm start`
5. Browse to <http://localhost:3000>

> Each packaged distribution includes some binaries for `sqlite3` and
> `libxmljs` bound to the OS and node.js version which `npm install` was
> executed on.

### Docker Container

[![Docker Pulls](https://img.shields.io/docker/pulls/bkimminich/juice-shop.svg)](https://hub.docker.com/r/bkimminich/juice-shop)
![Docker Stars](https://img.shields.io/docker/stars/bkimminich/juice-shop.svg)
[![](https://images.microbadger.com/badges/image/bkimminich/juice-shop.svg)](https://microbadger.com/images/bkimminich/juice-shop
"Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/bkimminich/juice-shop.svg)](https://microbadger.com/images/bkimminich/juice-shop
"Get your own version badge on microbadger.com")

1. Install [Docker](https://www.docker.com)
2. Run `docker pull bkimminich/juice-shop`
3. Run `docker run --rm -p 3000:3000 bkimminich/juice-shop`
4. Browse to <http://localhost:3000> (on macOS and Windows browse to
   <http://192.168.99.100:3000> if you are using docker-machine instead of the native docker installation)

### Vagrant

1. Install [Vagrant](https://www.vagrantup.com/downloads.html) and
   [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
2. Run `git clone https://github.com/bkimminich/juice-shop.git` (or
   clone [your own fork](https://github.com/bkimminich/juice-shop/fork)
   of the repository)
3. Run `cd vagrant && vagrant up`
4. Browse to [192.168.33.10:3000](http://192.168.33.10:3000)

### Amazon EC2 Instance

1. In the _EC2_ sidenav select _Instances_ and click _Launch Instance_
2. In _Step 1: Choose an Amazon Machine Image (AMI)_ choose an _Amazon Linux AMI_ or _Amazon Linux 2 AMI_
3. In _Step 3: Configure Instance Details_ unfold _Advanced Details_ and copy the script below into _User Data_
4. In _Step 6: Configure Security Group_ add a _Rule_ that opens port 80 for HTTP
5. Launch your instance
6. Browse to your instance's public DNS

```
#!/bin/bash
yum update -y
yum install -y docker
service docker start
docker pull bkimminich/juice-shop
docker run -d -p 80:3000 bkimminich/juice-shop
```

### Azure Container Instance

1. Open and login (via `az login`) to your
   [Azure CLI](https://azure.github.io/projects/clis/) **or** login to the [Azure Portal](https://portal.azure.com),
   open the _CloudShell_
   and then choose _Bash_ (not PowerShell).
2. Create a resource group by running `az group create --name <group name> --location <location name, e.g. "centralus">`
3. Create a new container by
   running `az container create --resource-group <group name> --name <container name> --image bkimminich/juice-shop --dns-name-label <dns name label> --ports 3000 --ip-address public`
4. Your container will be available at `http://<dns name label>.<location name>.azurecontainer.io:3000`

### Google Compute Engine Instance

1. Login to the Google Cloud Console and
   [open Cloud Shell](https://console.cloud.google.com/home/dashboard?cloudshell=true).
2. Launch a new GCE instance based on the juice-shop container. Take note of the `EXTERNAL_IP` provided in the output.

```
gcloud compute instances create-with-container owasp-juice-shop-app --container-image bkimminich/juice-shop
```

3. Create a firewall rule that allows inbound traffic to port 3000

```
gcloud compute firewall-rules create juice-rule --allow tcp:3000
```

4. Your container is now running and available at
   `http://<EXTERNAL_IP>:3000/`

## Demo

Feel free to have a look at the latest version of OWASP Juice Shop:
<http://demo.owasp-juice.shop>

> This is a deployment-test and sneak-peek instance only! You are __not
> supposed__ to use this instance for your own hacking endeavours! No
> guaranteed uptime! Guaranteed stern looks if you break it!

## Documentation

### Node.js version compatibility

![GitHub package.json dynamic](https://img.shields.io/github/package-json/cpu/bkimminich/juice-shop)
![GitHub package.json dynamic](https://img.shields.io/github/package-json/os/bkimminich/juice-shop)

OWASP Juice Shop officially supports the following versions of
[node.js](http://nodejs.org) in line with the official
[node.js LTS schedule](https://github.com/nodejs/LTS) as close as possible. Docker images and packaged distributions are
offered accordingly.

| node.js | Supported            | Tested             | [Packaged Distributions](#packaged-distributions) | [Docker images](#docker-container) from `master` | [Docker images](#docker-container) from `develop` |
|:--------|:---------------------|:-------------------|:--------------------------------------------------|:-------------------------------------------------|:--------------------------------------------------|
| 18.x    | :x:                  | :x:                |                                                   |                                                  |                                                   |
| 17.x    | :heavy_check_mark:   | :heavy_check_mark: | Windows (`x64`), MacOS (`x64`), Linux (`x64`)     |                                                  |                                                   |
| 16.x    | :heavy_check_mark:   | :heavy_check_mark: | Windows (`x64`), MacOS (`x64`), Linux (`x64`)     | `latest` (`linux/amd64`)                         | `snapshot` (`linux/amd64`)                        |
| 15.x    | (:heavy_check_mark:) | :x:                |                                                   |                                                  |                                                   |
| 14.x    | :heavy_check_mark:   | :heavy_check_mark: | Windows (`x64`), MacOS (`x64`), Linux (`x64`)     | `latest-arm` (`linux/arm/v7`, `linux/arm64`)     | `snapshot-arm` (`linux/arm/v7`, `linux/arm64`)    |
| 13.x    | (:heavy_check_mark:) | :x:                |                                                   |                                                  |                                                   |
| 12.x    | :heavy_check_mark:   | :heavy_check_mark: | Windows (`x64`), MacOS (`x64`), Linux (`x64`)     |                                                  |                                                   |
| <12.x   | :x:                  | :x:                |                                                   |                                                  |                                                   |

Juice Shop is automatically tested _only on the latest `.x` minor version_ of each node.js version mentioned above!
There is no guarantee that older minor node.js releases will always work with Juice Shop!
Please make sure you stay up to date with your chosen version.

### Troubleshooting

[![Gitter](http://img.shields.io/badge/gitter-join%20chat-1dce73.svg)](https://gitter.im/bkimminich/juice-shop)

If you need help with the application setup please check our
[our existing _Troubleshooting_](https://pwning.owasp-juice.shop/appendix/troubleshooting.html)
guide. If this does not solve your issue please post your specific problem or question in the
[Gitter Chat](https://gitter.im/bkimminich/juice-shop) where community members can best try to help you.

:stop_sign: **Please avoid opening GitHub issues for support requests or questions!**

### Official companion guide

[![Write Goodreads Review](https://img.shields.io/badge/goodreads-write%20review-49557240.svg)](https://www.goodreads.com/review/edit/49557240)

OWASP Juice Shop comes with an official companion guide eBook. It will give you a complete overview of all
vulnerabilities found in the application including hints how to spot and exploit them. In the appendix you will even
find complete step-by-step solutions to every challenge. Extensive documentation of
[custom re-branding](https://pwning.owasp-juice.shop/part1/customization.html),
[CTF-support](https://pwning.owasp-juice.shop/part1/ctf.html),
[trainer's guide](https://pwning.owasp-juice.shop/appendix/trainers.html)
and much more is also included.

[Pwning OWASP Juice Shop](https://leanpub.com/juice-shop) is published under
[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)
and is available **for free** in PDF, Kindle and ePub format on LeanPub. You can also
[browse the full content online](https://pwning.owasp-juice.shop)!

[![Pwning OWASP Juice Shop Cover](https://raw.githubusercontent.com/bkimminich/pwning-juice-shop/master/cover_small.jpg)](https://leanpub.com/juice-shop)

## Contributing

[![GitHub contributors](https://img.shields.io/github/contributors/bkimminich/juice-shop.svg)](https://github.com/bkimminich/juice-shop/graphs/contributors)
[![JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)
[![Crowdin](https://d322cqt584bo4o.cloudfront.net/owasp-juice-shop/localized.svg)](https://crowdin.com/project/owasp-juice-shop)
![GitHub issues by-label](https://img.shields.io/github/issues/bkimminich/juice-shop/help%20wanted.svg)
![GitHub issues by-label](https://img.shields.io/github/issues/bkimminich/juice-shop/good%20first%20issue.svg)

We are always happy to get new contributors on board! Please check
[CONTRIBUTING.md](CONTRIBUTING.md) to learn how to
[contribute to our codebase](CONTRIBUTING.md#code-contributions) or the
[translation into different languages](CONTRIBUTING.md#i18n-contributions)!

## References

Did you write a blog post, magazine article or do a podcast about or mentioning OWASP Juice Shop? Or maybe you held or
joined a conference talk or meetup session, a hacking workshop or public training where this project was mentioned?

Add it to our ever-growing list of [REFERENCES.md](REFERENCES.md) by forking and opening a Pull Request!

## Merchandise

* On [Spreadshirt.com](http://shop.spreadshirt.com/juiceshop) and
  [Spreadshirt.de](http://shop.spreadshirt.de/juiceshop) you can get some swag (Shirts, Hoodies, Mugs) with the official
  OWASP Juice Shop logo
* On
  [StickerYou.com](https://www.stickeryou.com/products/owasp-juice-shop/794)
  you can get variants of the OWASP Juice Shop logo as single stickers to decorate your laptop with. They can also print
  magnets, iron-ons, sticker sheets and temporary tattoos.

The most honorable way to get some stickers is to
[contribute to the project](https://pwning.owasp-juice.shop/part3/contribution.html)
by fixing an issue, finding a serious bug or submitting a good idea for a new challenge!

We're also happy to supply you with stickers if you organize a meetup or conference talk where you use or talk about or
hack the OWASP Juice Shop! Just
[contact the mailing list](mailto:owasp_juice_shop_project@lists.owasp.org)
or [the project leader](mailto:bjoern.kimminich@owasp.org) to discuss your plans!

## Donations

[![](https://img.shields.io/badge/support-owasp%20juice%20shop-blue)](https://owasp.org/donate/?reponame=www-project-juice-shop&title=OWASP+Juice+Shop)

The OWASP Foundation gratefully accepts donations via Stripe. Projects such as Juice Shop can then request reimbursement
for expenses from the Foundation. If you'd like to express your support of the Juice Shop project, please make sure to
tick the "Publicly list me as a supporter of OWASP Juice Shop" checkbox on the donation form. You can find our more
about donations and how they are used here:

<https://pwning.owasp-juice.shop/part3/donations.html>

## Contributors

The OWASP Juice Shop core project team are:

- [Björn Kimminich](https://github.com/bkimminich) aka `bkimminich`
  ([Project Leader](https://www.owasp.org/index.php/Projects/Project_Leader_Responsibilities))
  [![Keybase PGP](https://img.shields.io/keybase/pgp/bkimminich)](https://keybase.io/bkimminich)
- [Jannik Hollenbach](https://github.com/J12934) aka `J12934`
- [Timo Pagel](https://github.com/wurstbrot) aka `wurstbrot`

For a list of all contributors to the OWASP Juice Shop please visit our
[HALL_OF_FAME.md](HALL_OF_FAME.md).

## Licensing

[![license](https://img.shields.io/github/license/bkimminich/juice-shop.svg)](LICENSE)

This program is free software: you can redistribute it and/or modify it under the terms of the [MIT license](LICENSE).
OWASP Juice Shop and any contributions are Copyright © by Bjoern Kimminich & the OWASP Juice Shop contributors
2014-2022.

![Juice Shop Logo](https://raw.githubusercontent.com/bkimminich/juice-shop/master/frontend/src/assets/public/images/JuiceShop_Logo_400px.png)
