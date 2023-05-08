# Open-source: Project Pythia - Learning Python Geoscience Software

## Talk with the Expert

### *This event is hosted by EDS book, Climate Informatics and Environmental Data Science Journal*

*Event facilitators:* Alejandro Coca-Castro and Anne Fouilloux

*Bring along your favourite hot/cold drink, snack and questions about the talk. And, while you wait for the event to start - please read more about the chairs, speaker and the event in this document. 🌻*

   * Date: 08 May 2023, Monday
   * Time: 16:00 - 17:00 UTC+1 (London time) (starting time in your time zone: [https://arewemeetingyet.com/London/2023-05-08/16:00](https://arewemeetingyet.com/London/2023-05-08/16:00) )
   * How you can join? Eventbrite page > [https://www.eventbrite.co.uk/e/talk-with-the-expert-open-source-software-pythia-project-brian-rose-tickets-631136695847](https://www.eventbrite.co.uk/e/talk-with-the-expert-open-source-software-pythia-project-brian-rose-tickets-631136695847) <--- Please register to receive a Zoom link
   * *All questions, comments, and recommendations are welcome on this Etherpad or on Zoom chat!*

Talk with the Expert features advances in open and reproducible research as part of the CIimate Informatics 2023 Reproducibility Challenge, [https://eds-book.github.io/reproducibility-challenge-2023](https://eds-book.github.io/reproducibility-challenge-2023).

*Thank you for joining us! We’re delighted to have you here.*

## 🗣️Welcome!

   * Please note that this call will be recorded
   * The video will be available on the EDS book YouTube channel in the next days: [https://www.youtube.com/channel/UC148zpdIEfRun-cUJbgbIyg](https://www.youtube.com/channel/UC148zpdIEfRun-cUJbgbIyg)
   * Turn on your webcam if you don’t mind sharing your face (or off if you do!)
   * Reminder: 
       * Code of conduct: [https://github.com/alan-turing-institute/environmental-ds-book/blob/master/CODE\_OF\_CONDUCT.md](https://github.com/alan-turing-institute/environmental-ds-book/blob/master/CODE\_OF\_CONDUCT.md) 
       * If you experience or witness unacceptable behaviour, or have any other concerns, please report it by contacting the project members (environmental.ds.book@gmail.com, acoca@turing.ac.uk).
       * To report an issue at this event involving one of the organisers, please email one of the members individually (acoca@turing.ac.uk, annef@simula.no)
       * We have enabled the closed caption (live transcription), please click on 'cc' at the bottom of your Zoom screen

## ⁉ Open Q \& A  

*The zoom room will remain open from 16:30-17:00 UTC+1 for an open Q\&A. This part of the call will not be recorded, and is optional for both speakers and the audience.*

   * What are the resources limitations for the nightly checks if any?
       * Binder service is limited and will be improved, there is funding from NSF to run a better Binder service
       * The basics does not run on Binder but is based on Github actions which works well for small examples
       * Some notebook require more resources, and hence this new Binder service
   * How to get in touch?
       * Pythia homepage tweeter, github, discourse, weekly meetings open to the public
   * Are you planning to make Healthy Workflows of Project Pythia available in GitHub Market place?
       * Not found yet the right way to do that, built for cookbooks, ought to be made available to other people (proposal submitted @NSF to go further)
   * Where di I get some info about the upcoming Hackathon in June in person at Boulder and online?
       *  [https://projectpythia.org/pythia-cookoff-2023/README.html](https://projectpythia.org/pythia-cookoff-2023/README.html)
   *

## 📝 Notes, comments and references by attendees

   * Overview of Project Pythia
       * Motivation: Geoscience is moving to OSS and cloud computing but there exists a lack of training resources for all tools/packages/dependencies
   * Foundations book: a collection of Binderized tutorials to go from zero to expert
   * Gallery: a catalogue of helpful resources and exemplary notebooks
   * Cookbooks: advanced and domain-specific tutorials and example workflows
       * "Cook-Off" from 20-23 June in collaboration with NCAR: [https://projectpythia.org/pythia-cookoff-2023/README.html](https://projectpythia.org/pythia-cookoff-2023/README.html)
       * It is a collection of notebooks with described software environment which is regularly tested to check that it works as it should (and badges show pass/fail accordingly). 
   * Demo: Example of notebook on a laptop using data on the Goolge cloud (CMIP6) that plots a time series of surface air temperature. Now to share it with the rest of the world, clean the notebook, on Github. Create a new repo, give breif description, include all branches, already prepopulated (.gitignore, license, etc.). In the action tab change permissions. Upload the CMIP6 notebook from the laptop (drag \& drop), commit this. Edit the environment.yml to add matplotlib, xarray, pandas, intake.ems, fsspec, gcsfs, nc-time-axis.in the .config.yml update the title, author, and email. Update the table of content (\_toc.yml) with the name of the file of the Jupyter notebook. Update Readme.md (title). The book is being built in the background as a Github action and the result goes to github-pages. After deployment the notebook is rendered as a web page, but the outputs from the Notebook are not stored in the repo itself.
   * This is very similar to what we are doing in the reproducibility Challenge
       * That could be excellent source material for the Pythia cookbook

## References shared

   * Project Pythia home: [https://projectpythia.org/](https://projectpythia.org/)
   * Foundations book: [https://foundations.projectpythia.org/](https://foundations.projectpythia.org/)
   * Cookbook gallery: [https://cookbooks.projectpythia.org/](https://cookbooks.projectpythia.org/)
   * GitHub org: [https://github.com/ProjectPythia](https://github.com/ProjectPythia)
   * Discussion board: [https://discourse.pangeo.io/c/education/project-pythia/](https://discourse.pangeo.io/c/education/project-pythia/)
   * Meeting calendar: [https://projectpythia.org/index.html#meeting-event-calendar](https://projectpythia.org/index.html#meeting-event-calendar)
   * Summer hackathon: [https://projectpythia.org/pythia-cookoff-2023/](https://projectpythia.org/pythia-cookoff-2023/)
   * Live Cookbook demo with CMIP6 data *(these links won’t work until the live demo, since we’ll create them in real time)*
       * Source: [https://github.com/brian-rose/cmip-demo-cookbook/](https://github.com/brian-rose/cmip-demo-cookbook/)
       * Rendered book: [https://brian-rose.github.io/cmip-demo-cookbook/](https://brian-rose.github.io/cmip-demo-cookbook/)
   * Project Pythia (formerly the Education Working Group)
       * Schedule: Mondays at 3p US Eastern Time (alternating between Project Pythia Education and Infrastructure Working Groups)
       * Conferencing: Zoom [https://ucar-edu.zoom.us/j/91375487587](https://ucar-edu.zoom.us/j/91375487587) (consult the Pythia Calendar: [https://calendar.google.com/calendar/u/0?cid=Y180cXB2ZjMxNmFmZDltdjBjaTdkMnVpYWZvZ0Bncm91cC5jYWxlbmRhci5nb29nbGUuY29t](https://calendar.google.com/calendar/u/0?cid=Y180cXB2ZjMxNmFmZDltdjBjaTdkMnVpYWZvZ0Bncm91cC5jYWxlbmRhci5nb29nbGUuY29t) for how to join)
       * Notes: [https://docs.google.com/document/d/e/2PACX-1vQN5YFkZtCZPKVk2Rte2xoHuiqJuYz1KpynsSKmeCLwP-4glUsGuCPJbITwB4OJc8dOhUpHAMacdx59/pub](https://docs.google.com/document/d/e/2PACX-1vQN5YFkZtCZPKVk2Rte2xoHuiqJuYz1KpynsSKmeCLwP-4glUsGuCPJbITwB4OJc8dOhUpHAMacdx59/pub)

## Useful links

   * CIimate Informatics 2023 Reproducibility Challenge, [https://eds-book.github.io/reproducibility-challenge-2023](https://eds-book.github.io/reproducibility-challenge-2023).
   * EDS book: [https://edsbook.org/](https://edsbook.org/) 
   * Climate Informatics: [http://www.climateinformatics.org/](http://www.climateinformatics.org/)
   * Environmental Data Science - part of Cambridge University Press and Assessment, [https://www.cambridge.org/core/journals/environmental-data-science](https://www.cambridge.org/core/journals/environmental-data-science)

## Feedback

What worked?

   *
   * 

What didn’t work?

   *
   * 

What would you change?

   *
   * 

What surprised you?

   *
   * 

License: EDS book CC BY 4.0 adapted from Fireside chats template ([https://github.com/alan-turing-institute/the-turing-way/blob/cb557e2c0441b5f8669627c23e5686ec7faf96ff/book/website/community-handbook/templates/template-fireside-chat.md)](https://github.com/alan-turing-institute/the-turing-way/blob/cb557e2c0441b5f8669627c23e5686ec7faf96ff/book/website/community-handbook/templates/template-fireside-chat.md)) provided by The Turing Way provided under CC BY 4.0.

Timer: [https://cuckoo.team/ci2023-talk-expert](https://cuckoo.team/ci2023-talk-expert)