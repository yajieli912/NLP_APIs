# NLP APIs
## How to connect to AWS Comprehend:
1. create new or use existing IAM
2. pip3 install awscli --upgrade --user
3. ~/Library/Python/3.6/bin/aws configure
4. region: us-east-1
5. file type: json


## How to connect to Google Cloud:
1. In GCP Console, navigate to the Create service account key page.
2. From the Service account dropdown, select New service account.
3. Input a name into the form field.
4. From the Role dropdown, select Project > Owner.
5. Click the Create button. A JSON file that contains your key downloads to your computer.
6. Run this in terminal: export GOOGLE_APPLICATION_CREDENTIALS="[PATH]"
