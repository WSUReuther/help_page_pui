# Help Page PUI

This ArchivesSpace plugin adds a Help page to the ArchivesSpace Public User Interface

## Installation

Clone this repository to `/path/to/archivesspace/plugins` and enable the plugin by editing the `/path/to/archivesspace/config/config.rb`:

```
AppConfig[:plugins] = ['help_page_pui']
```

## How it Works

This plugin adds a Help menu entry to the ArchivesSpace navigation bar that directs users to the contents of `public/views/help/index.html.erb`