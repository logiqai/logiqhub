# logiqhub

Find, install and publish LOGIQ dashboards for popular applications. 

## Contribution guidelines

If you have a LOGIQ dashboard to share with the world, we'd love to host it for you! To submit your dashboard, do the following:

1. Create a new folder at the root level to house your dashboard. 
2. Name it according to the service, device, or application your dashboard serves. For example, if you're creating a dashboard for Azure Event Hubs, name it `azure-event-hubs`. 
3. Add your dashboard JSON files to this folder. 
4. Add a readme with the following headings:
    - Title
    - Features
    - Configuration
    - Steps to import
    - Screenshots
5. Edit the `index.html` file at the root of this repository. 
6. Look for the section starting with `<!---LIST OF LOGIQHUB DASHBOARDS-->` and edit the HTML to add an entry to your dashboard on the homepage of [LOGIQHub](https://logiqhub.logiq.ai/).
7. Be sure to include the following:
    - A logo for the service, device, or application your dashboard serves. 
    - A title against the HTML element `<h5 class="card-title" style="font-weight: bolder;">TITLE</h5>`
    - A short description of the dashboard's functionality against the HTML element `<p class="card-text">DESCRIPTION</p>`
    - A link to your dashboard folder against `<div class="btn-group"><a href="Dashboard URL"</a></div>`
8. Raise a PR to merge your changes to the `master` branch. 

We'll then quickly review your submission and publish it for the world to see and use. 

