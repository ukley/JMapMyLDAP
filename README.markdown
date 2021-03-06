<h1>JMapMyLDAP</h1>
<p>Welcome to the project home for JMapMyLDAP (jmmLDAP).</p>
<p>Currently, the main site at <a href="http://shmanic.com/tools/jmapmyldap">http://shmanic.com/tools/jmapmyldap</a> contains all the documentation and updates for this project.
<p>Discussions for this tool can be found in the Joomla! Forums <a href="http://forum.joomla.org/viewtopic.php?f=46&t=657124">http://forum.joomla.org/viewtopic.php?f=46&t=657124</a></p>

<h2>Version Information</h2>
<p>Version <strong>1.x</strong></p>
<ul>
 <li>Requires Joomla! 1.6, 1.7 or 2.5+</li>
 <li>Released: September 2011</li>
 <li>Github repository available at <a href="https://github.com/ShMaunder/JMapMyLDAPv1">https://github.com/ShMaunder/JMapMyLDAPv1</a></li>
</ul>

<p>Version <strong>2.x</strong></p>
<ul>
 <li>Requires Joomla! 2.5+ or Joomla! Platform 11.3+</li>
 <li>Test builds available</li>
</ul>

<h2>Building</h2>
<p>Use the included build.sh script to generate each individual extension from this project. This script requires Phing and xmlstarlet.</p>
<p>There is also a server hosting pre-built packages found at <a href="http://server.shmanic.co.uk/jmml_builds">http://server.shmanic.co.uk/jmml_builds</a>.</p>

<h2>Known Issues</h2>
<ul>
 <li>SSO framework and configuration need to fully support jauthtools-sso plug-ins for more advanced SSI/SSO solutions</li>
 <li>Several issues relating to first time logging into an existing LDAP account with user creation enabled</li>
 <li>When on fail delete option is enabled in user creation and trying to create a non-joomla but existing LDAP user, it deletes the LDAP user because it fails</li>
 <li>Groups do not save to LDAP after creating a new user through the Joomla user manager</li>
 <li>Username change code is missing meaning sites should disable it</li>
</ul>
