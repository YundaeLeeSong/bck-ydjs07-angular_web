npm install -g @angular/cli

-g means global



ng --version
ng new sns-blog

npm run ng g c component/pokeSearch





Linting is the automated process of checking your source code for programmatic and stylistic errors before the code is even executed




The editor or IDE you choose is essentially just the outer UI shell. The actual "brain" that turns standard TypeScript and HTML into an intelligent Angular environment is the Angular Language Service.  Because this tool is built as a standard Language Server Protocol (LSP), it behaves like a universal plug-in. No matter which environment you use, it hooks in behind the scenes to deliver the essential features:  Cross-File Intelligence: It links your .component.ts file to your .component.html template. If you have a variable named userProfile in your TypeScript, it instantly autocompletes and type-checks it inside your HTML.Instant Error Detection: It catches broken property bindings, mismatched inputs, or typos in template expressions directly in the editor before you even run a build.  Modern Syntax Mapping: It maps out structural directives and modern Angular template blocks (like @if, @for, and signals), providing accurate type inference when you hover over them.Whether you run Kiro or standard VS Code, installing the official Angular Language Service extension gives you the exact same foundation used across the entire software industry. It’s the single most important step in setting up your workspace.