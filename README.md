*Sysload Agent Diagnostic*
=============


This program performs different actions on SP Analyst Agents
http://github.com/Automic-Community/Sysload-Agent-Diagnostic

<!-- List of attached files -->
Contents of Solution Package:

						
								*Agent_Diagnostic.zip
								
						


Documenation and Instructions
---

<p>This program performs different actions on SP Analyst Agents:<br /> - Given an Agent Group, check whether the Agents can be reached. If not, deactivate the flag "Used for SP Portal".<br /> - For each machine of that Group, given a list of Metric IDs, check if Agents do have those metrics in the history file for the previous day (% of information greater than a threshold value).<br /> - Generate a report in text.<br /> <br /> Contains:<br /> - A PHP library for querying Management Server.<br /> - A base class for a batch program<br /> - A class for a log file...<br /> <br /> Information is collected by querying Sysload Management Server API.<br /> <br /> The actual work starts in function "execute" of "class_program.php".</p>
<p>&nbsp;</p>
<p><strong class="title">Prerequisites:</strong></p>
<ul>
<li>PHP 5.x.</li>
<li>A network connection to Sysload Managment Server</li>
</ul>
<p><strong class="title">Implementation:</strong></p>
<p>Unzip the contents. Customize files.</p>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)



Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
