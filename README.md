# CleanPush — public pages

The privacy policy, terms of use, and support page for
[CleanPush: Push Ups to Scroll](https://apps.apple.com/app/id6791178885), served
by GitHub Pages at <https://soloranez21.github.io/cleanpush-app/>.

- <https://soloranez21.github.io/cleanpush-app/privacy/>
- <https://soloranez21.github.io/cleanpush-app/terms/>
- <https://soloranez21.github.io/cleanpush-app/support/>

## Do not edit the HTML here

Every page is generated. The sources live in the app repo under `docs/legal/`
(`privacy-policy.md`, `terms-of-use.md`, `support.md`, and `site.json` for the
values substituted into them). To change a page:

```
# in the CleanPush repo
scripts/build-legal-site ~/Desktop/cleanpush-app
cd ~/Desktop/cleanpush-app && git commit -am "docs: update" && git push
```

Anything from the first `---` rule onward in a source file is an internal note
and is stripped before publishing.
