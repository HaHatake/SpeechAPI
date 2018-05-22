# SpeechAPI
api call

read this webpage

https://cloud.google.com/speech/docs/getting-started?hl=ja
https://qiita.com/knyrc/items/7aab521edfc9bfb06625
https://audio.online-convert.com/convert-to-flac


Complete outh service accoount work

uproad audio file to google cloud strage
 and finish open that file

start google cloud shell 

"pip install --upgrade google-cloud-speech"

"sudo curl -LO https://raw.githubusercontent.com/HaHatake/SpeechAPI/master/speechapi"

"python speechapi.py gs://"yourbacket"/"youraudiofile.flac"

wait for 5min ~ 10min 

output  jp,utf-8 character file

end of the job


***** if y encounter error ******
api return this code
"Long-running operation had neither response nor error set"

is yr audio file type ?
 maybe, m4a.
 Speech API Recommendation flac and 16000Hz audio.
 i try conversion flac type in this site
 https://audio.online-convert.com/convert-to-flac
