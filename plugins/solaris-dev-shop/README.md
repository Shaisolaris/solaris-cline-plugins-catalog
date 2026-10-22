# Solaris Dev Shop

61 specialist workflows plus a chief-of-staff coordinator, with complete source, local recovery and evidence helpers, and a native solaris_intake tool.

## Install

After the source package is published to npm and this entry is accepted into the official collection:

```sh
cline plugin install solaris-dev-shop
```

For a local collection checkout:

```sh
cline plugin install ./plugins/solaris-dev-shop --cwd .
```

The manifest loads the complete product through a versioned npm source-package dependency. Its declared entrypoint belongs to that installed package; Cline discovers the package's bundled skills. Source is not copied or reformatted in this collection. Exact reviewed candidate: https://github.com/Shaisolaris/solaris-dev-shop-cline/commit/7d884ae7187b290024956b4a8013937672b22977 . Native adapter, verification and CI: https://github.com/Shaisolaris/solaris-dev-shop-plugins/pull/12 .

## Requirements

Cline CLI3.0.73 or compatible SDK0.0.95, Python3.10+ and PyYAML on PATH for local helpers. This uses Cline's CLI/SDK/Kanban plugin support; it does not claim VS Code or JetBrains plugin support. Individual specialist workflows retain their own documented tools and approvals.

## Example

Ask Cline to call solaris_intake with request "review this code". The local coordinator returns one accountable code-review assignment. An underspecified request returns the legitimate clarification decision. It does not run specialist work or manufacture a completed review.

## Security and data

Installation fetches the complete source package from the npm registry. No lifecycle scripts are declared. Runtime registration adds the skills and one bounded local tool. The tool accepts only one request field, caps UTF-8 input at32KiB, invokes the pinned coordinator through execFile without a shell and after an argument separator, uses a20second timeout and a minimal child environment. It adds no lifecycle hooks, MCP servers, background jobs, provider settings or automatic permission approvals. It makes no model calls or network requests itself. Host permissions still apply.

The product preserves1197 canonical source files and original notices. Source packages are MIT licensed; all third-party notices stay in the dependency. Publisher: Solaris Technologies, https://solaristek.com. Support: https://github.com/Shaisolaris/solaris-dev-shop-plugins/issues .

## Pending publisher gate

The source package is not yet published to npm. This local entry is not submitted and the catalog install keyword is not available. The verified direct public Git package remains independent of this catalog gate. No npm policy is weakened to permit Git or arbitrary URL dependencies.
