
## Default Variables

### android_file_transfer_started

Start in background after install

#### Default value

```yaml
android_file_transfer_started: true
```

### android_file_transfer_user

User to run user-specific commands

#### Default value

```yaml
android_file_transfer_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
