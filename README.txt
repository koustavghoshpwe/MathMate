MATHMATE — GRADUATE-COVERAGE FREE STARTER

WHAT IT DOES
- Android-installable Progressive Web App (PWA).
- No paid API key, login, subscription, or application server.
- Uses Pyodide + SymPy in the browser for symbolic mathematics.
- Includes simplify, solve, factor, expand, differentiation, integration, limits, Taylor series, ODE solving, matrix analysis, number factorisation/primality, descriptive statistics, numerical evaluation, Laplace transform, Fourier transform, infinite summation, gradient, Jacobian, Hessian, divergence and curl.
- Subject selector now includes postgraduate topics (functional analysis, measure theory, PDEs, distribution theory, Lie theory, representation theory, algebraic topology, differential geometry, manifolds/tensors, algebraic geometry) and engineering mathematics (numerical PDEs, finite elements, control theory, signal processing, fluid/continuum mechanics, electromagnetics, quantum mathematics, reliability, optimisation, operations research and information theory).
- Optional photo-to-text via Tesseract.js. OCR is experimental; verify every symbol.
- Shows a detailed method outline and result.

IMPORTANT LIMITATIONS
The advanced subject names are included as study categories; only the listed symbolic operations are implemented as working tools. This is a broad mathematical toolkit, not a general AI tutor. SymPy does not solve every possible graduate-level question. This version does not fully automate topology, measure theory, advanced abstract algebra, research-level proofs, arbitrary word problems, or diagram-based geometry. Its explanations describe the method but do not derive every internal symbolic transformation. Matrix input should be typed like [[1,2],[3,4]]. For ODEs use SymPy notation, e.g. Eq(Derivative(y(x),x), y(x)); the general ODE interface is experimental.

COST / INTERNET
No paid API or API key. On first use, internet is needed to download Pyodide, SymPy and OCR libraries from public CDNs. The app's own files are cached for repeat visits, but calculation engines may need internet/CDN availability. GitHub Pages can host a public repository for free.

INSTALL ON ANDROID
1. Extract this ZIP.
2. Create/sign in to a GitHub account.
3. Create a NEW public repository named mathmate.
4. Upload index.html, manifest.webmanifest, sw.js and icon.svg to the repository root (not the ZIP itself).
5. Open repository Settings → Pages.
6. Under Build and deployment, choose Deploy from a branch; choose main and /(root), then Save.
7. Wait for GitHub Pages to publish. Open the displayed HTTPS website in Chrome on Android.
8. Chrome menu (⋮) → Install app, or Add to Home screen.
9. Open MathMate from your home screen.

TROUBLESHOOTING
- If the engine remains loading, check internet and reload.
- If OCR is wrong, edit the text manually.
- Use explicit parentheses and * for multiplication when possible.
- For a proof identity, choose Proof checking and enter LHS=RHS.
- This is a learning aid; independently verify important results.
