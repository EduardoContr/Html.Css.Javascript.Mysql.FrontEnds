# Html.Css.Javascript.Mysql.FrontEnds
This repo includes modules, components, that were developed in the Linux/Apache/Mysql/php(/python/perl) stack.  Using php in the CMS (Content Management Systems)
in production and Xamp stack locally one would sftp/ftp via Cute Ftp or various others (clients include Filezilla/mozilla etc) from dev to prod environs to share, 
commit, push, edit(/make editss) to the application; MVC structure (Model Viewer Controller) framework with files allocated accordingly enforced.  
It is generally most common and easiest way to segregate single files by type, eg., images in folder for Views (.png), web pages includeing those referenced in 

code snippet start/end tags:
<a href ='path:webpage'>aboutwebpagename.com</a>) tags), 

stored in  view folders containing the items for header, footer and menus (.php) (callable with include php statements)

and index.php controller files would be calling webpages and images from the controller file in controller folder.file using include statements.  

Scripts included in "scrip"file I wrote here would be included once, written in one section for reuse in line with the template functionality used w. php.
Therefore products containing images and prices of merchandise would include one connection string reused across all pages requesting such data so user could browse by
women's, men's, feature and related category.  Php is known for object oriented syntax.  See file attached "scrip" to see an example where calling a connection 
string stored as a variable (which has a connection user name, database table name and password) would not be retyped at every page.  Note objects are stored for queries 
by feature, eg., men's category, "wedding ring" feature. eg., or gold-plated-14k, white-gold, gold-18k, platinum, features eg.'s.

#Oracle,Mysql Notes
Pages requesting data about customers, their orders and company products rely on php scripts to embed sql for queries about data.  Such data is stored in backend.
Content retrieved from back end was stood up in myphpadmin a GUI simplifying the ddl (data definition Language) used for column storeage and definition;
the creation of tables includes the selection of primary, unique, data type settings/values li mits of column headers. 
Data was inputted manually or using the import functionality to get data from csv or excel files by selecting the appropriate data delimitter, eg., 
carriage return /n or /,.
#Templates of Php and headers
Head section would separately call and include style sheets (cascading style sheets to provide attributes for color and backgrounds, size of text and useability with mobile 
aps or broser IE version, mozilla, firefox, google etc, javascript code for functionality such as pull down menus and on-click events. These are saved in 
separate folder not the controller, main file for reuse. Template is the php use of these sections on each page, such as about us, products, category or more info pages.
Haing developed code for clients (jewelry stores, small business and government ) php was chosen and content management systems went from cots to niche systems,
Drupal, Joomla for example with prepopulated themes and templates of greater detail. 
#mysql
Database queries in php are embedded in sql syntax on a php page.  This scrip document aka "scrp" has a model
php connect script in sql syntax to connect the front to backend on that Lamp stack for that Content Management System ipage vendor in this case).
Separate files stored in this repo show views of products and categories fro backend in sql.
