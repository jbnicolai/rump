# Changelog

### 0.6.1
- Emit event for adding Gulp tasks
- Check for `optionalDependencies` in autoload

### 0.6.0
- **BREAKING**: Use `addGulpTasks` instead of `taskPrefix`/`setTaskPrefix`
- Update `del` and `require-all`
- Add and set up for `lint:` tasks

### 0.5.0
- Drop Rump and Gulp dependencies in packages (user use minor version)

### 0.4.0
- Drop use of `peerDependencies` (use `npm dedupe`)

### 0.3.0
- Remove task prefix by default

#### 0.2.3
- Add option to change task name prefix
- Add `:prod` tasks for tasks with production

#### 0.2.2
- Add reconfigure option

#### 0.2.1
- Add version information to info task

### 0.2.0
- Initial alpha version
