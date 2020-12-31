## ARTiC2 ATOMIC YAML

ARTiC2 Atomic YAML is a collection of Atomic YAML instructions and technique dependencies forked from [@redcanaryco](https://github.com/redcanaryco). ARTiC2 uses them to dynamically extract, build, organize, and execute ARTiC2 instructions as fire-and-forget techniques. All techniques are executed from memory and mapped to the [MITRE ATT&CK Framework](https://attack.blackbot.io). 


## HOW THEY'RE USED

**For each Atomic YAML**

- ARTiC2 reads the YAML stored in each [atomics folder](https://github.com/blackbotinc/ARTiC2-Atomic-YAML/tree/master/atomics) 
- Decides which C2 delivery controllers are required
- Builds corresponding C2 instructions and PowerShell scripts
- Organizes technique dependencies such as c# code, DLLs, binaries, etc.
- Pushes new technique test cases and corresponding dependencies to the [ARTiC2's TTP directory](https://github.com/blackbotinc/Atomic-Red-Team-Intelligence-C2/tree/master/blackbot/core/wss/ttp)

**NOTE** In some cases, techniques and/or dependencies are modified to ensure evidence is collected by ARTiC2 with the intent to make it easier for security teams to evaluate if techniques are blocked without the need to triage IOCs on the breach point in question.  

**Check out the ARTiC2 Repo** [here](https://github.com/blackbotinc/Atomic-Red-Team-Intelligence-C2)


## GOT QUESTIONS?

- Hit us up on Slack at [https://blackbotlabs.slack.com](https://blackbotlabs.slack.com)


## CODE OF CONDUCT

Blackbot Labs operates under the umbrella of full transparency while ensuring end-user privacy remains a top priority. For more details on how we operate with our community, visit our community [Code of Conduct page.](https://blackbot.io/code-of-conduct)

## CREDITS & ACKNOWLEDGEMENTS
- [byt3bl33d3r](https://github.com/byt3bl33d3r) from Black Hills Security 
- The folks at [Red Canary](https://redcanary.com/) and everyone's code used to develop red team atomic test cases


## LICENSE
[MIT License](https://github.com/blackbotinc/ARTiC2-Atomic-YAML/blob/master/LICENSE)

