# Run Microsoft Edge Automation
Getting the lastest Edge and the latest MSEdgeDriver


We have these files that list the latest WebDriver binary version of each Edge channel that you can download from that site:

https://msedgedriver.azureedge.net/LATEST_BETA

https://msedgedriver.azureedge.net/LATEST_CANARY 

https://msedgedriver.azureedge.net/LATEST_STABLE 

https://msedgedriver.azureedge.net/LATEST_DEV 

 

For WebPlatformTests, we use this script to download and install Edge: https://github.com/web-platform-tests/wpt/blob/master/tools/ci/azure/install_edge.yml

 

And then use this to download Edge driver: https://github.com/web-platform-tests/wpt/blob/4398d74fea97068f29499dcd1c6d6d6b268b9940/tools/wpt/browser.py (line 1016).
