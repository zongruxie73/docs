---
title: Using GitHub Copilot in GitHub Codespaces
intro: 'You can use {% data variables.product.prodname_copilot %} in {% data variables.product.prodname_github_codespaces %} by adding the extension.'
versions:
  fpt: '*'
  ghec: '*'
type: reference
topics:
  - Codespaces
  - Copilot
  - Visual Studio Code
shortTitle: Copilot in Codespaces
redirect_from:
  - /codespaces/codespaces-reference/using-copilot-in-codespaces
  - /codespaces/codespaces-reference/using-github-copilot-in-codespaces
---

{% jetbrains %}

{% data reusables.codespaces.codespaces-jetbrains-beta-note %}

{% endjetbrains %}

{% webui %}

## Using {% data variables.product.prodname_copilot %} in the {% data variables.product.prodname_vscode_shortname %} web client

{% data reusables.codespaces.copilot-in-vscode %}

{% endwebui %}

{% vscode %}

## Using {% data variables.product.prodname_copilot %} in {% data variables.product.prodname_vscode %}

{% data reusables.codespaces.copilot-in-vscode %}

{% endvscode %}

{% jetbrains %}

## Installing {% data variables.product.prodname_copilot %} in your JetBrains IDE

[{% data variables.product.prodname_copilot %}](https://copilot.github.com/), an AI pair programmer, can be used in any codespace. For more information, see "[AUTOTITLE](/copilot/overview-of-github-copilot/about-github-copilot-for-individuals)."

To use {% data variables.product.prodname_copilot %} in a codespace in your JetBrains IDE, install the [{% data variables.product.prodname_copilot %} plugin](https://plugins.jetbrains.com/plugin/17718-github-copilot) from within your codespace.

{% note %}

**Note**: You must install the {% data variables.product.prodname_copilot %} plugin each time you create a new codespace.

{% endnote %}

1. In the JetBrains client application, open the Settings (Windows/Linux) or Preferences (Mac) dialog:

   - **Windows/Linux**: Click **File** and then **Settings** (or press <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>S</kbd>)
   - **Mac**: Click **JetBrains Client** in the MacOS menu bar, then click **Preferences** (or press <kbd>command</kbd>+<kbd>,</kbd>)

1. In the left-side menu of the Settings/Preferences dialog, click **Plugins On Host**. Then click the **Marketplace** tab.

   ![Screenshot of the "Preferences" dialog, with the "Marketplace" tab displayed. The "Plugins On Host" option is highlighted with a dark orange outline.](/assets/images/help/codespaces/jetbrains-preferences-plugins.png)

1. In the search box, type "copilot" then click the **Install** button for the {% data variables.product.prodname_copilot %} plugin.

   ![Screenshot of the "Preferences" dialog, with the GitHub Copilot plugin displayed. The "Install" button is highlighted with a dark orange outline.](/assets/images/help/codespaces/jetbrains-copilot-plugin.png)

1. Click **Accept** in the "Third-Party Plugins Privacy Note" dialog.
1. Click **Restart IDE**.
1. Click **Restart** when prompted to confirm that you want to restart the backend IDE that's running remotely. The JetBrains client application will close when you do this.
1. After your JetBrains IDE has restarted, click the **Tools** menu. Click **{% data variables.product.prodname_copilot %}**, then click **Login to {% data variables.product.prodname_dotcom %}**.

    ![Screenshot of the menu bar on a Mac. In the "Tools" menu, the "{% data variables.product.prodname_copilot %}" submenu is displayed, and "Login to {% data variables.product.prodname_dotcom %}" is selected.](/assets/images/help/codespaces/jetbrains-tools-menu.png)

1. In the "Sign in to {% data variables.product.prodname_dotcom %}" dialog, to copy the device code and open the device activation window, click **Copy and Open**.

    ![Screenshot of the device code copy and open](/assets/images/help/copilot/device-code-copy-and-open.png)

1. A device activation window will open in your browser. Paste the device code, then click **Continue**.

   - To paste the code in Windows or Linux, press <kbd>Ctrl</kbd>+<kbd>v</kbd>.
   - To paste the code in macOS, press <kbd>command</kbd>+<kbd>v</kbd>.
1. {% data variables.product.prodname_dotcom %} will request the necessary permissions for {% data variables.product.prodname_copilot %}. To approve these permissions, click **Authorize {% data variables.product.prodname_copilot %} Plugin**.
1. After the permissions have been approved, your JetBrains IDE will show a confirmation. To begin using {% data variables.product.prodname_copilot %}, click **OK**.

## Further reading

- "[AUTOTITLE](/copilot/getting-started-with-github-copilot/getting-started-with-github-copilot-in-a-jetbrains-ide)"

{% endjetbrains %}
