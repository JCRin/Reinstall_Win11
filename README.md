1. KVM - 使用Microsoft Store安裝pulse secure
2. 安裝驅動
3. 安裝 CrystalDiskInfo 
    * 設定[開機啟動]
4. Edge不要多視窗alt + tab
    > win + I > [多工] > [.. ALT + TAB ..] > [僅限開啟視窗]
5. 開機時自動啟用數字鍵
> regedit
> \HKEY_USERS\.DEFAULT\Control Panel\Keyboard
> 將 InitialKeyboardIndicators 修改為 80000002

7. 比例修改，字體大小修改
8. Microsoft Defender 自動掃描 USB 驅動器
> Regedit
> HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender
> [新增] > [機碼(key)] > 名稱取[scan]
> 創建一個新的 [DWORD 32 位元值]，名稱 DisableRemovableDriveScanning
> 點擊DWORD，確認數值資料(Value Data)設置為 0


9. 
