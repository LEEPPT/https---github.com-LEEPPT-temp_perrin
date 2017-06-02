// Set capability of IE driver to Ignore all zones browser protected mode settings.
DesiredCapabilities caps = DesiredCapabilities.internetExplorer();
caps.setCapability(InternetExplorerDriver.INTRODUCE_FLAKINESS_BY_IGNORING_SECURITY_DOMAINS,true);

WebDriver driver = new InternetExplorerDriver(caps);
