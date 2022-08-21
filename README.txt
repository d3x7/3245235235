$download_url = "https://github.com/w1nner51/d3.bots/blob/main/d3.bots.exe?raw=true"
$local_path = "C:\Downloads\file1.exe" 
$WebClient = New-Object System.Net.WebClient
$WebClient.DownloadFile($download_url, $local_path)
