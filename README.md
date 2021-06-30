# terality-demo-notebooks

Terality is the serverless data processing engine for data science. Find out more at www.terality.com.

This repository contains Python notebooks demonstrating how to use Terality. To run these notebooks, you'll need a Terality account.
Contact us (https://www.terality.com/contact, contact@terality.com) to get started.

## Writing Terality client code

Copy the file containing your account information (provided by Terality) to `$HOME/.terality/config.json`.
Install the Python client library: `pip install terality`.

Terality uses the same API as the `pandas` library: simply replace `import pandas as pd` by `import terality as pd` and you are good to go.

There is no infrastructure to configure or manage. You can run the code from your laptop without needing to
worry about processing time or memory issues.

Terality integrates with many storage providers, such as AWS S3 or Azure Data Lake. You can process data
stored on any of these storage providers. Uploading local files is also supported.

## Want more information?

Feel free to write to us at `contact@terality.com`, we're happy to answer any question.
