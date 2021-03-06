# Firefox 21 annoyances


This week Firefox 21 was released
and there are two features of it that have irritated me.

First off, nowhere did I see an
obvious prompt or mention that there's now a feature (Firefox Health
Report, FHR) that collects general browser, non-user data. It's not a
big deal since this comprises anonymous browser statistics only. On the
other hand, the fact that I didn't see any notification or an
opt-in/opt-out prompt on upgrading irks me.
(I only learned about it from
[The
Register](http://www.theregister.co.uk/2013/05/15/firefox_21_health_report/).)

From Mozilla's FHR [FAQ](http://blog.mozilla.org/metrics/fhr-faq/):

> "We believe in giving users
> power over data, even data like this that isn’t personally identifiable
> or linkable to our users. FHR gives Firefox users control over data
> submitted by their browser. Users can use FHR data to better understand
> their browser’s performance or stability by comparing it to that of
> aggregate data from other browser configurations. At any time users can
> disable the feature or delete data associated with their browser."

Fine. It would have been nice to,
you know, actually make certain that users were aware of this feature
though.

Secondly, and more directly annoying, left clicking on an MP3, which
would show a save/open prompt, now starts playing the MP3 instead. (I'm
assuming this feature is new in Firefox 21, since I can't remember it
being present previously. I'm also aware that you can right-click, and
then choose Save Link As…, but it's easier to just left-click.)

My initial thought was to check the list of MIME types (Options \>
Applications) to see if anything had changed. No, it still looked just
as it did before:

<img class="article-image" src="{static}/images/2013/Firefox_MIME_types.png" alt="Firefox MIME types">

The about:config option to restore the original behaviour is to set
[media.windows-media-foundation.enabled to
false](http://forums.mozillazine.org/viewtopic.php?f=23&t=2698835),
although this disable in-browser playback of some other media formats.
Again, it's not a big problem, but it's counter-intuitive to let the
user set an option that purportedly controls what happens when a link is
clicked, and then ignore it for no discernable reason.

