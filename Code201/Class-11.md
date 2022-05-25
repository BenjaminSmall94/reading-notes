# Audio, Video, Images

[Home](../index.md)

## HTML and CSS

### Chapter 16: Images

#### Size of Images

Detailing the size of images in CSS is good practice because it allows the webpage to load before the image becuase the browser will know how much space to reserve for the image during page rendering. Whenever you have consistently sized images across a webpage it is good practice to style them in CSS using classes instead of HTML inline styling in order to have cleaner code.

#### Aligning Images in CSS

Using the float property is a very common way to align images (rather than using the align attibute of `<img>` tags) Again using classes to indicate which way the image will be aligned is a very common practice. In order to center images you need to convert them into block or inline block elements and then either do `text-align: center` of the containing element of set the left and right margins of the image itself to auto.

#### Background Image

The background image allows you to place an image behind an HTML element. By default it will repeat to fill the entire element. The path is specified in the CSS `background-image` attribute with the following syntax `url("...")`.

The `background-repeat` attribute can have four values, `repeat`, `repeat-x`, `repeat-y`, and `no-repeat` and they do exactly what they sound like they do. The `background-attachment` attribute lets you specify if an image will scroll with the page or stay fixed in the viewer. The `background-position` attribute allows a developer to place a background image wherever they'd like to place it. It comes with predefined positionings or the developer can specify exact pixels or percentages from the top left corner of the browser (or the containing element depending on the `background-attachment` value). Also you can use shorthand to specify these values too.

### Chapter 19: Practical Information

#### Search Engine Optimization

Search engine optimization (SEO) is the process of getting your website to appear nearer the top on a search engine list. Search engines look at the content of your site, but also how many other sites link to your site and the importance of those sites as well. Therefore SEO is primarily broken down into two parts, on-page techniques and off-page techniques.

##### On-page techniques

SEOs look at many items on your page to determine what the website is about and how important your website is. Therefore it is improtant to use keywords in your site so that search engines can pick up on this. The seven most important places to put these keywords are:

1. Page Title
2. URL / Web Address
3. Headings
4. Text
5. Link Text
6. IMG Alt Text
7. Page Descriptions

Make sure you put effort into identifying keywords that users might use in order to find your website.

##### Off-page techniques

It is just as important to get other sites to link to yours. It is most beneficial if the site linking to your site is about a similar topic. When you can help it be sure the link to your site contains relevant text as well. Search engines will weight these kinds of links with higher signifigance.

#### Page Analytics

After people start visiting your site you can start collecting information about them eg where they are from and how they found your website. Google Analytics is a very good free analytics website and requires that you sign up fro an account. Some useful information provided by Google Analytics is:

- Visits
- Unique Visits
- Page Views
- Page Views per Visist
- Average Time on Site
- Date Selector
- Export
- Pages
- Landing Pages
- Top Exit Pages
- Bounce Rate
- Referrers
- Direct
- Search Terms

#### Domain Names and Hosting

Your domain name is your website address. One certain company is responsible for ensuring proper protocols is followed with website names and making sure that now duplicate names are created.

 > The Internet Corporation for Assigned Names and Numbers (ICANN) is the non-profit organization that oversees the assignment of both IP addresses and domain names. It has responsibility for managing root server and TLD name system management and has contractual agreements with both registries and registrars that provide the foundation for the WHOIS system.

ICANN then gives special authority to Registrars who can frequently sell certain domain names to Web Hosting Services to act as resellers.

It is possible therefore to buy a Domain name and publish a website from your local computer after setting it up to act as a server but it is much more common and usually economical to simply pay a Web Hosting service to publish your website and they will have very little down time and include maintenance on the servers.

#### FTP & Third Party Tools

In order to transfer files between your computer and the web hosting company's servers you can use a File Transfer Protocol program.

## MDN Audio Visual Article

The `<audio>` and `<video>` tags allow you to embed media into your webpage. You are able to specify exactly what controls you want. This is important becuase the native controls of each browser are different so each user could get a significantly different experience interacting with the media. The HTML media element makes it easy to set up your own custom controls via JavaScript. It provides all the functionality you will need in order to build your own custom interface.

## Chapter 9 Flash, Video and Audio

Flash was a useful framework for creating animations or hosting audio/visual files.

## Things I want to Know More about

I really want to get practice using the setInterval function in JavaScript. I can see a lot of cool uses for that for instance building video game!
