# Scripts
General Scripts

$path = "c:\temp\test"
$Name = Import-Csv c:\temp\milestone-homes-file-layout1.csv
foreach ($i in $Name) {
New-Item -Path $path -Name $i.Name -ItemType Directory
}
