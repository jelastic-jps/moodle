[![Moodle](images/Moodle-logo.png)](../../../moodle)
## Moodle

The JPS package deploys Moodle that initially contains 1 application server and 1 database container. 

### Highlights
This package is designed to deploy Moodle environment which represents a learning platform, designed to provide educators and learners with a single robust.
- Modern, easy to use interface<br />
Designed to be responsive and accessible, the Moodle interface is easy to navigate on both desktop and mobile devices.
- Personalised Dashboard<br />
Organise and display courses the way you want, and view at a glance current tasks and messages.
- Collaborative tools and activities<br />
Work and learn together in forums, wikis, glossaries, database activities, and much more.
- All-in-one calendar<br />
Moodle’s calendar tool helps you keep track of your academic or company calendar, course deadlines, group meetings, and other personal events.
- Convenient file management<br />
Drag and drop files from cloud storage services including MS OneDrive, Dropbox and Google Drive.
- Simple and intuitive text editor<br />
Format text and conveniently add media and images with an editor that works across all web browsers and devices.
- Notifications<br />
When enabled, users can receive automatic alerts on new assignments and deadlines, forum posts and also send private messages to one another.
- Track progress<br />
Educators and learners can track progress and completion with an array of options for tracking individual activities or resources and at course level.

### Environment Topology

![Moodle Topology](https://docs.google.com/drawings/d/1rH4bL0JUhKmP5FLETQkY1myucPUKINr57k1ci15sD10/pub?w=505&h=216)

### Specifics

Layer                |     Server    | Number of CTs <br/> by default | Cloudlets per CT <br/> (reserved/dynamic) | Options
-------------------- | --------------| :----------------------------: | :---------------------------------------: | :-----:
AS                   | Apache 2 (MOD_PHP) |       1                        |           1 / 16                          | -
DB                   |    MySQL      |       1                        |           1 / 16                           | -

* AS - Application server 
* DB - Database 
* CT - Container

**Moodle Version**: 3.0.1<br/>
**PHP Engine**: PHP 5.4.45<br/>
**MySQL Database**: 5.7.12

### Deployment

In order to get this solution instantly deployed, click the "Get It Hosted Now" button, specify your email address within the widget, choose one of the [Jelastic Public Cloud providers](https://jelastic.cloud) and press Install.

[![GET IT HOSTED](https://raw.githubusercontent.com/jelastic-jps/jpswiki/master/images/getithosted.png)](https://jelastic.com/install-application/?manifest=https%3A%2F%2Fgithub.com%2Fjelastic-jps%2FMoodle%2Fraw%2Fmaster%2Fmanifest.jps)

To deploy this package to Jelastic Private Cloud, import [this JPS manifest](../../raw/master/manifest.jps) within your dashboard ([detailed instruction](https://docs.jelastic.com/environment-export-import#import)).

More information about Jelastic JPS package and about installation widget for your website can be found in the [Jelastic JPS Application Package](https://github.com/jelastic-jps/jpswiki/wiki/Jelastic-JPS-Application-Package) reference.