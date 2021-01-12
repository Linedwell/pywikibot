Current release changes
~~~~~~~~~~~~~~~~~~~~~~~

* Add support for niawiki, bclwikt, diqwikt, niawikt (T270416, T270282, T270278, T270412)
* Delete page using pageid instead of title (T57072)
* version.getversion_svn_setuptools function was removed (T270393)
* Add support for "musical notation" data type to wikibase
* -grepnot filter option was added to pagegenerators module (T219281)
* L10N updates

Future release notes
~~~~~~~~~~~~~~~~~~~~

* 5.5.0: Site.getuserinfo() method will be dropped in favour of userinfo property
* 5.5.0: Site.getglobaluserinfo() method will be dropped in favour of globaluserinfo property
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
