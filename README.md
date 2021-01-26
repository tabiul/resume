Using [jsonresume](https://jsonresume.org/) to generate my resume

I tweaked the template [paper template](https://github.com/TimDaub/jsonresume-theme-paper) a bit for the following reason

* I wanted to have a section called **technology** so that I can show what **technology** I used for each of my job
* The profiles were shown as hyperlinks which is pretty useless when someone prints the pdf :))

The template fix is hackish as that was the best I could od with my limited css skills :))

How to run

* `npm install`
* replace the `resume.template` to what is in this repo `cp resume.template node_modules/jsonresume-theme-paper`
* `resume export -f pdf -t paper tabiul-mahmood` to generate the resume

