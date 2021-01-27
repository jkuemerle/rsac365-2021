## Angular : Are you disabling HTTP cookie access to support Angular CSRF?
- [ ] No, but I am using some other mitigation to prevent CSRF
- [ ] Yes, and I am ensuring that cookie values are only non-sensitive data

## Are you using any insecure methods to set content values?
- [ ] No, I am only using safe framework methods to set content
- [ ] Yes, I am using insecure methods and I am ensuring that content is correctly encoded for the context that it rendered in.

## Are you allowing user provided content to aid in creating dynamic templates?
- [ ] No, I am only rendering user provided content as properly encoded content
- [ ] Yes, I am required to use user provided content as a part of a template and I am using an allowlist to mitigate the types of content to be rendered.

