# scrapy
Web Scrapper
- The notebook contains the code for my process in extracting jobs from the [ihub jobs website](https://ihub.co.ke/jobs)
- I saved the jobs as a json file that I'll export to mongodb
- EXporting to mongodb via this terminal command 
``` mongoimport --db scrapy --collection jobs --file ihub.json --jsonArray ```
- Check out the scrapy-edge repository where I build a flask endpoint to expose the jobs for use in a frontend app
which I'll also build.
