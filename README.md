<p><img src="https://blackbot.io/wp-content/uploads/2020/12/artic2_atomics_logo_v2.png" width="700px" /></p>

## ARTiC2 ATOMICS

ARTiC2 Atomics are red team atomic tests forked from [@redcanaryco](https://github.com/redcanaryco) and are used by ARTiC2 to dynamically extract and build C2 instructions and PowerShell versions of each atomic test from memory. All techniques are mapped to the [MITRE ATT&CK Framework](https://attack.blackbot.io). 


## HOW THEY'RE USED

For each atomic test case:

- ARTiC2 reads the YAML files stored in each [atomics folder](https://github.com/blackbotinc/ARTiC2-Atomics/tree/master/atomics) 
- Decides which C2 delivery controllers are required
- Builds corresponding C2 instructions and PowerShell scripts
- Organizes dependencies such as c# code, DLLs, binaries, etc. used by each test case
- Pushes new test cases to the [ARTiC2's TTP directory](https://github.com/blackbotinc/Atomic-Red-Team-Intelligence-C2/tree/master/blackbot/core/wss/ttp)


## GOT QUESTIONS?

- Hit us up on Slack at [https://blackbotlabs.slack.com](https://blackbotlabs.slack.com)


## CODE OF CONDUCT

Blackbot Labs operates under the umbrella of full transparency while ensuring end-user privacy remains a top priority. For more details on how we operate with our community, visit our community [Code of Conduct page.](https://blackbot.io/code-of-conduct)


## LICENSE
[MIT License](https://github.com/blackbotinc/artic2-atomics/blob/master/LICENSE)
