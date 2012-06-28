cssRefresh
=======
Based on http://cssrefresh.frebsite.nl/

Have been using this since quite a some time but when you are using Google Font API or any other external CSS source then it used to try and realod that as well. Add a small patch to avoid doing that.

Also a variable duration is defined to control interval of reload