# Leaky phone apps


My phone doesn't have a huge number of third party apps installed, but
saw this chart today and it's a little worrying nonetheless:

<figure class="article-figure">
  <img src="{static}/images/2013/Free_apps_chart.jpg" alt="Chart showing a substantial proportion of free apps collect data such as location.">
  <figcaption>Chart courtesy of <a href="http://www.statista.com/topics/876/android/chart/1228/free-apps-are-hungry-for-user-data/">Statista</a>.</figcaption>
</figure>

I'm not sure exactly what "account info" describes. I did check the
[original
report](http://www.juniper.net/us/en/forms/mobile-threats-report/) but
it's not defined there either. Also, I'm not sure whether the authors
corrected for the fact that some apps might require some information —
e.g. location access for some kind of mapping app — to actually be
useful. As a result, these numbers could be an overestimate of the
actual number of apps that are doing something unexpected with your
data. Furthermore, it might explain why even a substantial proportion of
paid apps require these permissions. (For ad-supported apps, location
information might be requested for some [targeted advertising
component](https://en.wikipedia.org/wiki/Location-based_advertising) of
the app.)

It's unlikely that Google will ever allow fine control of app
permissions to enable the user to install an app without necessarily
giving it access to e.g. your address book. The only options on stock
Android are to take the app, warts and all, or do without. So,
definitely worth considering installing
[PDroid]({filename}../2013/patching-android-roms-for-pdroid-using.md)
to help deal with this issue.

