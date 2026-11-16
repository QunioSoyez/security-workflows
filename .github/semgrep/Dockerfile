# NOT BUILT OR RUN. Notifier only.
# Dependabot can't update the Semgrep image pinned in .github/workflows/security-scan.yml
# (container: image: ...), so this file lets Dependabot's "docker" ecosystem watch it.
# When Dependabot opens a PR here, copy the new tag + digest into security-scan.yml
# (container: image: semgrep/semgrep@sha256:<digest> # <version>) in the same PR, then tag a new release.
FROM semgrep/semgrep:1.185.0@sha256:67518c174185a2043fdbed16c70631b79209499b3671178e7194379b48295a0d
