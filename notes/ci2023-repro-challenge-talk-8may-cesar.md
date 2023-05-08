# Open-source: Preparing remote sensing data for deep learning using r-spatial

## Talk with the Expert

### *This event is hosted by EDS book, Climate Informatics and Environmental Data Science Journal*

*Event facilitators:* Alejandro Coca-Castro and Anne Fouilloux

*Bring along your favourite hot/cold drink, snack and questions about the talk. And, while you wait for the event to start - please read more about the chairs, speaker and the event in this document. 🌻*

   * Date: 08 May 2023, Monday
   * Time: 09:00 - 10:00 UTC+1 (London time) (starting time in your time zone: [https://arewemeetingyet.com/London/2023-05-08/09:00](https://arewemeetingyet.com/London/2023-05-08/09:00) )
   * How you can join? Eventbrite page > [https://www.eventbrite.co.uk/e/talk-with-the-expert-open-source-software-r-spatial-cesar-luis-aybar-tickets-631112042107](https://www.eventbrite.co.uk/e/talk-with-the-expert-open-source-software-r-spatial-cesar-luis-aybar-tickets-631112042107) <--- Please register to receive a Zoom link
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

*The zoom room will remain open from 09:30-10:00 UTC+1 for an open Q\&A. This part of the call will not be recorded, and is optional for both speakers and the audience.*
   * Where should I start looking for r packages?
       * R Advance book
       * Spatial R > Edzer Pebesma
       * Communities
   * Comparison between Planetary Computer and GEE?
   * Can we get the cloud percentage from satellite images using R language and information obtained in the graph by pixel location? 
       * RSToolbox
       * Download from the satellite data themselves

## 📝 Notes, comments and references by attendees

   * CloudSen12: [https://cloudsen12.github.io/](https://cloudsen12.github.io/) Datasets for cloud detection for ML/DL
   * interoperatibilty between Python \& R: rpy2 from Python to R and reticulate from R to Python
   * R is very rich for spatial data analysis.
   * There is also this type of notebook called script of scripts ([https://vatlab.github.io/sos-docs/](https://vatlab.github.io/sos-docs/) ), which I haven't used too much but is supposed to be a multilingual notebook that allows you to use R and Python (and other languages) in one notebook
   * Example for modelling Sentinel 2 BOA from TOA, code will be shared after the talk
       * Steps:
           * Authenticate to GEE
           * Define the study area > reprojection using the sf package
           * Spatial sampling to get patches/kernels of paired  TOA/BOA images > hard-core point process (HCPP), a variant of the ramdon sampling using a specified minimun distance >
               * HCPP offers a better representation of the study area
           * Generate patches
           * Run DL in Torch
           * Export model

## References shared

   * rOpenSci Champions Program
       * [https://ropensci.org/champions/](https://ropensci.org/champions/)
   * R-advanced: [https://adv-r.hadley.nz/](https://adv-r.hadley.nz/)
   * R-spatial book: [https://r-spatial.org/book/](https://r-spatial.org/book/)
   * Demo [Code]: [https://github.com/csaybar/RPythonsync](https://github.com/csaybar/RPythonsync)
   * Slides: [https://docs.google.com/presentation/d/1Ws2o5WwcRMcYd9YjKcfyLv5X4lOAwJztEU1sMRADTVk/edit?usp=sharing](https://docs.google.com/presentation/d/1Ws2o5WwcRMcYd9YjKcfyLv5X4lOAwJztEU1sMRADTVk/edit?usp=sharing)

## Useful links

   * CIimate Informatics 2023 Reproducibility Challenge, [https://eds-book.github.io/reproducibility-challenge-2023](https://eds-book.github.io/reproducibility-challenge-2023).
   * EDS book: [https://edsbook.org/](https://edsbook.org/) 
   * Climate Informatics: [http://www.climateinformatics.org/](http://www.climateinformatics.org/)
   * Environmental Data Science - part of Cambridge University Press and Assessment, [https://www.cambridge.org/core/journals/environmental-data-science](https://www.cambridge.org/core/journals/environmental-data-science)

## Feedback`

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