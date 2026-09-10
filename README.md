# Tapo Section Workbench

Private team distribution of the Tapo Section Workbench Codex plugin.

## Install

1. Download `tapo-section-workbench.zip` from this repository and extract it.
2. Open a terminal in the extracted folder containing `.agents` and `plugins`, then run:

```sh
codex plugin marketplace add "$PWD"
codex plugin add tapo-section-workbench@tapo-internal
```

3. Connect your own Shopify account. Install the Shopify plugin for development skills and ensure Visualize and browser tools are available.
4. Start a new Codex task and say **Open Tapo Section Workbench**.

Keep the extracted folder in place: it is the local marketplace source. The archive includes the complete plugin source, marketplace manifest, and detailed README. The plugin manifest passed validation.

Repository owners can invite colleagues through **Settings → Collaborators**. Store permissions are managed separately in Shopify.

The plugin shares the workflow and reference assets. It does not include account credentials, chat history, or sections created in previous tasks. Existing draft-theme sections remain available in Shopify.

## Store and draft selection

The opening form requires a country/market, store handle, and the Theme Editor URL of your explicitly chosen unpublished draft. Use **Help me choose a draft theme** to request a read-only list from your store. No UK store or theme is preselected. Codex verifies the selected store and theme before writing and stops if the theme is live or inaccessible. Existing installations must reinstall this updated package and start a new task.

## Attach reference images

Attach images and other references directly in the Codex chat composer, using the paperclip or drag and drop, before submitting the Brief. The form does not transfer files. Select **I have attached the references in this chat**; Codex must inspect those attachments before coding and ask if they are missing.
