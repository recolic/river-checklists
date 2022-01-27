# Can access P.R.China LAN but can not access Internet - PC

1. Check your [taskbar](./deps/systray.jpg) and make sure [OpenVPN](./deps/ovpn-logo.png) is **not** running. If it is running, [right-click and exit it](./deps/ovpn-exit.png). 
2. Launch FireFox. Set [SwitchyOmega](./deps/what-is-switchyomega.md) to `Auto Switch / 自动切换` Mode.
3. Visit <https://www.aliyun.com> and see if it's working. If problem got resolved, **stop executing remaining steps**. 
4. Launch FireFox. Set [SwitchyOmega](./deps/what-is-switchyomega.md) to `Direct / 直接连接` Mode.
5. Visit <https://www.aliyun.com> and see if it's working. **If problem got resolved**, click [SwitchyOmega](./deps/what-is-switchyomega.md) and select `Options / 选项`, follow [this guide](./deps/switchyomega-confreset1.png) **AND THEN** [this guide](./deps/switchyomega-confreset2.png) to modify your settings. Then set [SwitchyOmega](./deps/what-is-switchyomega.md) to `Auto Switch / 自动切换` Mode, and **stop executing remaining steps**.

## If step 4 did not resolve the issue

There is something wrong with your network. Try the following steps: 

1. Start [OpenVPN](./deps/ovpn-logobig.png). If you don't know how to start it, refer to [this guide](https://support.microsoft.com/en-us/windows/find-all-your-apps-and-programs-cadb9c4b-459d-dfcb-2964-14aac1d7d964#WindowsVersion=Windows_10). 
2. Right-Click [OpenVPN icon](./deps/ovpn-logo.png) in system tray, select Suzhou node, and "Connect". 
3. See if the problem got resolved. 

