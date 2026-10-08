# Animavyr Privacy Policy

Last updated: 2026-05-30

## 1. Summary

Animavyr does not collect user account data, usage analytics, crash reports, cloud project content, or telemetry by default. The App is designed to keep stories, characters, scenes, images, videos, audio, workflows, and output files in the user's local workspace or browser storage.

## 2. Data Stored Locally

The App may store the following data on your device:

- The workspace handle you choose and the contents of your project folders.
- Project settings, workflow settings, prompt templates, AI Copilot templates, and interface preferences.
- Local settings, recently used projects, UI state, and browser authorization information in IndexedDB.
- Text, images, videos, audio, workflow JSON, metadata, and output files that you create or import.
- Local license files, license state, edition information, and expiration dates used by the Tauri desktop build.

This data is primarily kept on your local disk or in browser storage. By default, Animavyr does not send this data to servers controlled by Animavyr.

License verification currently uses local offline validation. The license file may be placed at `license.animavyr.json` in the App configuration directory, or selected through the `ANIMAVYR_LICENSE_FILE` environment variable. If server activation, account login, or online license synchronization is added later, Animavyr will update this policy before enabling it and explain the data that will be transmitted.

## 3. Local AI / Generation Services and Custom Workflow Endpoints

The App currently directly supports only locally run or user-connected LM Studio and ComfyUI. When you run AI analysis, prompt assistance, image / video / audio generation, workflow tasks, or resource coordination, the App may send the following data to the local LM Studio or ComfyUI endpoints you configure:

- Prompts, story excerpts, character settings, scene descriptions, camera information, and user instructions.
- Reference images, videos, audio, or compressed / transformed versions of them.
- ComfyUI workflow JSON, node parameters, generation settings, task IDs, and status queries.
- Output file URLs or file requests needed to retrieve generated results.

ComfyUI workflows, custom nodes, or model nodes that you import or customize may include external API calls. When you run such workflows, the data listed above may be transmitted to service endpoints configured by you or specified by the workflow. Animavyr does not control those endpoints' data retention, logs, models, network security, license terms, or privacy policies. You are responsible for verifying whether an endpoint is trusted, local or cloud-hosted, and suitable for confidential project materials or client data.

## 4. No Telemetry by Default

The current version does not collect by default:

- App usage analytics.
- Automatic crash reports.
- Device identifiers or advertising identifiers.
- Cloud project content.
- User behavior analytics events.

If telemetry, error reporting, cloud backup, account login, or synchronization services are offered in the future, Animavyr will update this policy before collection begins, explain the data categories, purposes, retention periods, third-party processors, and opt-out method, and provide any required consent or opt-out choices.

## 5. File System Access API and Browser Permissions

The App uses the browser File System Access API to read and write the workspace you choose. You can revoke folder access through your browser permission settings.

If permission expires, the App may ask you to reauthorize the workspace so it can continue reading and writing project data. Revoking permission does not automatically delete project files from your local disk.

## 6. Retention and Deletion

You can delete workspaces, project folders, output files, workflows, and assets through your file system. Local settings in browser IndexedDB can be removed through browser site-data controls, the App's reset settings feature, or future clearing tools.

Deleting local data may not delete data already transmitted to LM Studio / ComfyUI endpoints you configured, or to external APIs triggered by custom workflows. Please use the relevant service's policies, logs, and deletion mechanisms.

## 7. Children and Sensitive Data

The App is not specifically designed for children. You should not input highly sensitive personal data, children's data, medical data, financial data, identity documents, confidential business data, or protected third-party content unless you have lawful authorization or consent.

## 8. Security

Animavyr uses a local-first design, but local security still depends on your device, browser, workspace location, local LM Studio / ComfyUI endpoints, external APIs that custom workflows may connect to, and network environment. You should use backups, disk encryption, permission controls, anti-malware tools, and trusted endpoint settings as appropriate.

## 9. Policy Updates

This policy may be updated as product features, distribution methods, platform requirements, or legal requirements change. Material changes will be notified through the App, website, release page, or another reasonable method.
