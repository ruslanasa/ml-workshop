Run params:

--runner=DataflowRunner
--input=gs://ml-workshop-vilnus/personal
--output=gs://ml-workshop-vilnus/sample
--tempLocation=gs://ml-workshop-vilnus/temp
--gcpTempLocation=gs://ml-workshop-vilnus/temp

Create default credentials:
gcloud auth application-default login

Env var for app to be authenticated, or add to run config into environment:
export GOOGLE_APPLICATION_CREDENTIALS=~/.config/gcloud/legacy_credentials/oleksiimo\@wix.com/adc.json

Search for "Dataflow API" on google cloud console and enable it. Then play again.
