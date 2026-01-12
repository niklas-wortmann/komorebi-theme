[2026-01-12 12:47] - Updated by Junie - Error analysis
{
    "TYPE": "env/setup",
    "TOOL": "plugin.xml validation",
    "ERROR": "plugin.xml must not contain template text 'IntelliJ'",
    "ROOT CAUSE": "Template plugin.xml was not updated and still uses disallowed template name.",
    "PROJECT NOTE": "Update plugin.xml: set unique id, Komorebi theme name/vendor, and register the theme extension.",
    "NEW INSTRUCTION": "WHEN semantic errors mention template text in plugin.xml THEN update id, name, vendor, and extensions"
}

[2026-01-12 14:24] - Updated by Junie - Error analysis
{
    "TYPE": "invalid args",
    "TOOL": "search_replace",
    "ERROR": "Unresolved reference 'TestFrameworkType' in build.gradle.kts",
    "ROOT CAUSE": "The import was removed but the testFramework(TestFrameworkType.Platform) usage remained in the script.",
    "PROJECT NOTE": "For a pure theme plugin, remove testFramework configuration and test dependencies entirely from build.gradle.kts.",
    "NEW INSTRUCTION": "WHEN build.gradle.kts references TestFrameworkType THEN remove testFramework block and its imports"
}

