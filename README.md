Xcode Doxygen Helper
====================

A very basic helper script to make it less onerous to document code in Xcode 5.

Many thanks to Fredd McCann for writing this awesome utility. 

The original script and more detailed usage information can be found here:
  http://duckrowing.com/2011/05/14/using-the-doxygen-helper-in-xcode-4/


## Changes:

I changed it for the original script as follows:

  * Support ruby 2.0 (OS X Mavericks and Xcode 5.0.x)
  * Comment style for doxygen

### New comment style:

    /**
     * <#Description#>
     */
    @interface AppDelegate : UIResponder <UIApplicationDelegate>

    /**
     * <#Description#>
     * 
     * @param application <#application description#>
     * @param launchOptions <#launchOptions description#>
     * @return <#return value description#>
     */
    - (BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions

## How to install

  1. Copy 'Document Code.workflow' into '~/Library/Services'.
  2. Assign a keyboard shortcut in system settings.

## How to use

  In Xcode text editor:

  1. Select a class declaration or a method signature.
  2. Press the assigned keyboard shortcut.

## How to uninstall

  1. Remove the assigned keyboard shortcut in system settings.
  2. Remove 'Document Code.workflow' in '~/Library/Services'.

