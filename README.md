Windows key bindings scheme for Eclipse

This plugin provides Windows key bindings for Eclipse on MacOS.
To activate these key bindings, click <strong>Window > Preferences > General > Keys</strong>. Then as Scheme, select "WinKey4Mac".

The key bindings are defined using specific keys (CTRL, ALT, SHIFT) in the Windows scheme, i.e. these binding do NOT use the platform independent Eclipse key codes (M1, M2, M3, M4).

Update site:
`http://download.pjp.org/updates/winkey4mac`

To build on JDK 1.8:
run: `mvn clean install`

To perform manual install copy the build artifacts into the `eclipse/dropins` directory and restart Eclipse:

    org.pjp.winkey4mac.bindings-1.0.0-SNAPSHOT.jar
    org.pjp.winkey4mac.bindings.feature-1.0.0-SNAPSHOT.jar
