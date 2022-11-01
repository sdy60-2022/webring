# Webring

This webring contains the students' CVs.

## How to add your CV to the webring

* Edit webring/data/members.json
* Add a record following this format:

        {
            "title": "Καμπουρόπουλος Π.",
            "url": "https://panoskam.github.io/",
            "feed": null
        }
* Commit and Send Pull Request

(note the title formatting: last name, then first letter of your first name and a period)

## How to add Banner Embed code to your CV

* Open your CV source html file
* Add the following piece of code at an appropriate location on your page

        <webring-banner>
                <p>Member of <a href="https://sdy60-2022.netlify.app/">ΣΔΥ60-2022 Ring</a></p>
                <a href="https://sdy60-2022.netlify.app/prev">Previous</a>
                <a href="https://sdy60-2022.netlify.app/random">Random</a>
                <a href="https://sdy60-2022.netlify.app/next">Next</a>
        </webring-banner>
        <script async src="https://sdy60-2022.netlify.app/embed.js" charset="utf-8"></script>

* Commit
