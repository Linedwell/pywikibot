Current release changes
~~~~~~~~~~~~~~~~~~~~~~~

* Re-enable reading user-config.py from site package (T270941)
* LoginManager.getCookie() was renamed to login_to_site()
* Deprecation warning for MediaWiki < 1.23 (T268979)
* Add backports to support some Python 3.9 changes
* Desupported shared_image_repository() and nocapitalize() methods were removed (T89451)
* pywikibot.cookie_jar was removed in favour of pywikibot.comms.http.cookie_jar
* Align http.fetch() params with requests and rename 'disable_ssl_certificate_validation' to 'verify' (T265206)
* Deprecated compat BasePage.getRestrictions() method was removed
* Outdated Site.recentchanges() parameters has been dropped
* site.LoginStatus has been removed in favour of login.LoginStatus
* L10N Updates

Future release notes
~~~~~~~~~~~~~~~~~~~~

* 5.4.0: Support of MediaWiki < 1.23 will be dropped with release 6.0  (T268979)
* 5.4.0: LoginManager.getCookie() is deprecated and will be removed
* 5.4.0: tools.PY2 will be removed (T213287)
* 5.3.0: api.ParamInfo.modules property will be removed
* 5.3.0: LogEntryFactory.logtypes property will be removed
* 5.3.0: stdout parameter of logging.output()/pywikibot.output() function will be desupported
* 5.1.0: Positional arguments of page.Revision must be replaced by keyword arguments (T259428)
* 5.0.0: HttpRequest result of http.fetch() will be replaced by requests.Response (T265206)
* 5.0.0: OptionHandler.options dict will be removed in favour of OptionHandler.opt
* 5.0.0: Methods deprecated for 5 years or longer will be removed
* 5.0.0: pagegenerators.ReferringPageGenerator is desupported and will be removed
