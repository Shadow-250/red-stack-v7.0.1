#### 7.0.0: Maintenance Release

Runtime
 - Increase timeouts in Subflow tests to minimise false positives
 - Update grunt-sass and add node-sass for node12 support
 - Fix timings of Delay node tests
 - #2340 Update JSONata to 1.7.0
 - Bump https-proxy-agent version
 - #2332 Fix error handling of nodes with multiple input handlers
 - Add script to generate npm publish script

Editor
 - #2328 Fix language handling in subflow node
 - Use default language if lng param not set in i18n req
 - #2326 Fix palette editor search visualization

Nodes
 - Delay: Fix delay to not pass through .reset and .flush props consistently
 - #2352 File: Using the ‘a msg per line’ the last line does not get msg.topic passed
 - #2339 HTTP Request: Check auth type on opening
 - HTTP Request: add units info

