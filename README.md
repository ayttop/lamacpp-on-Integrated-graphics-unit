# lamacpp-on-Integrated-graphics-unit




Run lama cpp on integrated graphics and is 3 times faster



Number of model layers  -ngl 40

 ./llama-cli -m ../phi-3.5-mini-instruct-q4_k_m.gguf -t 6 -p "what 4+5?" -c 128 -ngl 40

./llama-cli -m ../phi-3.5-mini-instruct-q4_k_m.gguf -t 6 -p "what 4+5?" -c 128




on cmd
write PowerShell
$startTime = Get-Date
./llama-cli -m ../phi-3.5-mini-instruct-q4_k_m.gguf -t 6 -p "what 4+5?" -c 128 -ngl 40
$endTime = Get-Date
$duration = $endTime - $startTime
Write-Host "Start Time: " $startTime
Write-Host "End Time: " $endTime
Write-Host "Duration: " $duration

Duration:  00:00:09.2066370
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

$startTime = Get-Date
./llama-cli -m ../phi-3.5-mini-instruct-q4_k_m.gguf -t 6 -p "what 4+5?" -c 128
$endTime = Get-Date
$duration = $endTime - $startTime
Write-Host "Start Time: " $startTime
Write-Host "End Time: " $endTime
Write-Host "Duration: " $duration

Duration:  00:00:26.1009414






An experience I would like to share and I want to know your results.



iam use
llama-b3604-bin-win-openblas-x64



