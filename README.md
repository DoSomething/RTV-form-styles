# RTV-form-styling
CSS styles for the Rock The Vote (RTV) form. Although the file is uploaded directly to their platform and managed there, we wanted to track changes made to this file in this repository. Additional information on how to customize styles and assets can be found [here](https://www.rockthevote.org/programs-and-partner-resources/tech-for-civic-engagement/online-voter-registration-platform/partner-ovr-tool-faqs/).

Partner form style overrides live in `partner.css` (this must be the name of the file uploaded to the partner portal). This is uploaded and submitted for approval via the RTV partner portal. 

To upload the `partner.css` file, you must [login](https://vr.rockthevote.com/login) (credentials are in LastPass):

1. Click **Customize** > **White Label** > **CSS**. 
2. Upload your file. There is no need to check the **remove** checkbox for the `Not Approved Version` file when uploading your updated file.
3. Click **Update**. 

Any assets (like images) can be referenced in our override file once they are also uploaded in the asset section of the RTV partner portal.

_Please note: you will not be redirected to another page after the upload completes. After the file successfully uploads, you will no longer see partner2.css in the file selector, and instead of the file name, you will see "No file chosen"._

It is possible to preview changes prior to submitting to approval. 

1. Click **Customize** > **White Label** > **Preview & Submission**. 
2. Click the Preview link. **Do not click Submit for approval until you are 100% sure you are satisfied with all changes / it's been QA'ed on Browserstack.**

_Note: The preview link only is active for about 15 mins. **ALSO NOTE!!!! When previewing your changes, you need to hard refresh the preview page in order to ensure you are looking at the page with the most recently uploaded file.** Also, after you upload your file as `partner.css` it will be referenced to on both preview and after it's approved as `partner2.css`._