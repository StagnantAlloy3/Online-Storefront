The Computer Store Augustine Collins

**Research Design:** When I worked at the campus computer store in 2019, we did not have a way for
customers to view our laptop offerings online. During covid, I was tasked to build a store page that could
allow incoming students to browser and purchase a computer from the store via our webpage on
duq.edu. This page was limited as it had to be contained within a single page in our CMS, and was
unable to leverage back-end technologies. This project is a redesign of my original project as a
standalone webpage. This iteration does not include server-side logic, however it would in a final
deployment.

**Design-making:** Reference below.

**Usability Testing:** One of the challenges with the old design was congestion. Due to everything needing
to be housed on one page, the layout was incredibly compact. Due to management decisions, there is
entirely too much text on the page. Assets were enlarged and given proper spacing, making for a less
claustrophobic-feeling site. I put the html/css/js bundle on a home server and had some friends test out
the site. Besides some spacing and alignment issues, most feedback was positive. One feature that was
dropped for final production was the filter section on the products page. Users felt that due to the
product volume being low, it was a better use of space to remove the filters and have product cards
span the width of the page.

**Styling Guide:** Bootstrap.css was updated with the appropriate styling. Buttons should follow the
following style:

Button-primary:
base color: #
border color: #
hover base: #
hover border: #
active color: #6F
active border: #6F
Button-Secondary:
base color: #19A
border color: #19A
hover base: #1BB
hover border: #1BB

<a> tag hover event was also changed to use the button-secondary base color. All other aspects of
styling were left stock with Bootstrap v5.22.2.
