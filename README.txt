$download_url = "http://download_ahyware/file1.zip"
$local_path = "C:\Downloads\file1.zip" 
$WebClient = New-Object System.Net.WebClient
$WebClient.DownloadFile($download_url, $local_path)
