# dsankouski's cv
Credits to [casual-markdown-cv](https://github.com/casualwriter/casual-markdown-cv)

## Generate html page
Select one of the html templates, and run:

```sh
template=resume.html
sed -z 's/<!--======= COPY ABOVE CODE AS HEADER, THEN FOLLOW WITH RESUME CONTENT IN MARKDOWN FORMAT =========-->.*//' < "$template" > my-resume.html
cat resume.md >> my-resume.html
```

