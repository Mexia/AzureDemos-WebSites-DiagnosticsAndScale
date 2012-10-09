AzureDemos-WebSites-DiagnosticsAndScale
==============

Update the ChirpyR application, Roll-it Back, Scale it

1.   Open the ChirpyR solution.
2.   Update Views\Homes\Index.cshtml and \Content\Site.css (line 205) change background color to #ff99ff
3.   `git add -u`
4.   `git commit -m "made site awesome"`
5.   `git push azure master`
6.   Highlight the efficiency of the git push. Only deltas are pushed up.
7.   Deployments tab > Redeploy the previous deployment slot.
8.   Scale tab > Free, Shared or Reserved, and number of instances.
