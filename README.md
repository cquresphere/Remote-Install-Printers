# Remote-Install-Printers
Remote install printers from print server to local Windows system

# Notice after mitigation of CVE-2021-34481 for print driver installation admin privilege is required on local host

# Requirememnts 

Remote-Install-Priners tool requires:
1. PowerShell 5.1
2. Modules: 
   - ActiveDirectory
   -  PrintManagement
   -  ImportExcel
3. External Tools: 
   - Psexec (Psexec64.exe) from Sysinternals Tools Suite


# Appearance 
![image](https://user-images.githubusercontent.com/72066881/138870889-fe86fae5-0a2c-4a25-8955-de69d3e08c2a.png)
This is how GUI looks like

# Features

1. You can search for printer between print servers. (to change print server click on combobox and choose)
![image](https://user-images.githubusercontent.com/72066881/139075500-756928cd-8b2d-421d-9d47-ff7dd425c164.png)

2. You can choose what type of action you want to perform

![image](https://user-images.githubusercontent.com/72066881/139075839-42f6a32f-c628-4969-8a44-70582da60d4c.png)

   - add printer to local host
   - add printer to remote host
   - send to the remote host file explorer window with printers on print server
3. You can add printer(s) using two methods (prefered first method)

![image](https://user-images.githubusercontent.com/72066881/139076816-4e5f780c-b1ae-4b13-a542-311a60b1331c.png)

4. You can generate printers report for selected print server to excel file (xlsx) 

![image](https://user-images.githubusercontent.com/72066881/139076549-a2c3597c-a0d1-4cf4-99e9-724027ffaaa8.png)

5. You can refresh list of printers for selected print server

![image](https://user-images.githubusercontent.com/72066881/139076719-7eec470b-e780-4ccb-ae21-86e4007dfb2a.png)

6. You can cancel and close tool

![image](https://user-images.githubusercontent.com/72066881/139076891-1f178047-7e4a-4656-b233-f024fcd471ec.png)

7. If you double click to selected printer you will open Microsoft Edge on address from port name for this printer. 
