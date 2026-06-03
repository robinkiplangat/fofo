# Pack Manifest Spec

Describe pack manifest format, validation rules, and an example.

Example manifest:

    {
      "manifest_version": "1.0",
      "name": "example-pack",
      "version": "0.1.0",
      "description": "Example pack",
      "size_bytes": 12345,
      "files": [
        {"path": "content/index.html", "hash": "sha256:..."}
      ]
    }