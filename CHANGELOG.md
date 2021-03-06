# Changelog

### v3.5.0 (2016-04-05)
- All validations are enabled on all branches by default

### v3.4.0 (2015-12-08)
- Skip capitalization check for autosquash commits

### v3.3.0 (2015-10-10)
- Add support for custom validators

### v3.2.0 (2015-10-03)
- Add option to re-open text editor

### v3.1.0 (2015-09-27)
- Allow execution from scripts and GUI clients

### v3.0.1 (2015-09-21)
- Allow granular configuration overrides

## v3.0.0 (2015-09-18)
- Rename SummaryPeriod validator to SubjectPeriod (can break existing config files)
- Add CapitalizeSubject validator

### v2.2.2 (2015-09-11)
- Fix bug where it wasn't working on the first commit of a repo.

### v2.2.0 (2015-09-09)
- Configuration files to customize behavior.

### v2.1.1 (2015-08-31)
- Compatibility for all POSIX shells.

### v2.1.0 (2015-08-29)
- Add `fit-commit uninstall` command

## v2.0.0 (2015-08-27)
- Breaking changes made to Git hook. If upgrading from an older version you'll need to re-run `fit-commit install` in your repos.

### v1.1.0 (2015-08-26)
- Add support for `git commit -v`.

### v1.0.4 (2015-08-26)
- Improve error output in Git hook.
