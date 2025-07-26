# 1pif-section-converter

Modify the 1Password .1pif file to write the section headlines to a text field. This allows keeping the headlines for Bitwarden.

### Motivation

Unfortunately, Bitwarden does not support sections and section headlines. When converting passwords from 1Password to Bitwarden, these sections, including their headlines, are lost.

While it might be slightly annoying that Bitwarden logins can look a bit more messy as a result, this change can even be critical if the headlines contained necessary info for the fields that follow.

As a solution, this converter provides a workaround by modifying 1Password's `.1pif` export file, and converts the sections into explicit fields.
