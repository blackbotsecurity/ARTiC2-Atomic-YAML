## ARTiC2 ATOMIC YAML

ARTiC2 Atomic YAML is a a collection of red team atomic test YAMLs forked from [@redcanaryco](https://github.com/redcanaryco) and are used by ARTiC2 to dynamically extract, build, and execute ARTiC2 instructions. All techniques are executed from memory and mapped to the [MITRE ATT&CK Framework](https://attack.blackbot.io). 


## HOW THEY'RE USED

For Atomic YAML

- ARTiC2 reads the YAML stored in each [atomics folder](https://github.com/blackbotinc/ARTiC2-Atomic-YAML/tree/master/atomics) 
- Decides which C2 delivery controllers are required
- Builds corresponding C2 instructions and PowerShell scripts
- Organizes technique dependencies such as c# code, DLLs, binaries, etc.
- Pushes new technique test cases to the [ARTiC2's TTP directory](https://github.com/blackbotinc/Atomic-Red-Team-Intelligence-C2/tree/master/blackbot/core/wss/ttp)


## GOT QUESTIONS?

- Hit us up on Slack at [https://blackbotlabs.slack.com](https://blackbotlabs.slack.com)


## CODE OF CONDUCT

Blackbot Labs operates under the umbrella of full transparency while ensuring end-user privacy remains a top priority. For more details on how we operate with our community, visit our community [Code of Conduct page.](https://blackbot.io/code-of-conduct)


## LICENSE
[MIT License](https://github.com/blackbotinc/ARTiC2-Atomic-YAML/blob/master/LICENSE)
