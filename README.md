Welcome to the repo! Thanks for checking things out. 

First and foremost, you are hereby invited to collaborate on these projects!


**What's this?**

Below you will find documentation for the clientsidenetworkcontrol project, the inspirations and aspirations for the project and the overall styles used.
To give you, the reader, as much context and insight as possible there is alot of information and that is all relevant to the rest in the fuller context.
In summary, the initial paragraphs are focused on providing a clear picture of what this project is, was, and intends to be.
The next part is a call to action to the Open Source communities.
That is followed by a detailed investigation into copyright infringement and wrongful usage of code directly from this project including comparisons to example why other similar projects are not related and evidence as to how, and why, and when, and where, and who-from, the projects that are nearly identical and certainly derivitives, are.
This also gives context as to why this is all here and why the other projects are included in this archive.

*and quickly a grievance regarding such matters:*
   **Unfortunately** rather than address a matter with respect, or at all, when a consumer/user has a question, several parties have opted to get all content on CSingendonks account hidden from the public. All without a single response, or attempt to even acknowledge anything was happening at all, by multiple representatives, contacted through multiple channels of communication. All without a single response. The absence of any input from these individuals and organizations is unprofesional and does no favours to any of the involved (or not involved, rather). The contents of this repo are not only documentation but working examples and a call to action. Please take 2 minutes to consider the information in this readme file before making any assumptions.
Thank You.

# ClientsideNetworkControl
The snapshot that’s been released isn't meant to be a polished, fully functional product; it’s intentionally bare-bones—a minimal demo meant to showcase some of the key functionalities that are under active refinement behind the scenes in the private project. Here’s what’s happening:

A Showcase, Not the Full Project: The publicly available version is an incomplete snapshot. It's like a teaser that highlights core features of the ClientsideNetworkControl project without presenting all the robust integrations and refined functionality currently being developed privately. Think of it as a work-in-progress demo that illustrates the vision and direction of the project while intentionally leaving room for collaborative input and further development.

Dealing with Clones and Uncredited Copies: Over time, thousands of clones and direct copycats of the concept have cropped up, yet none of these derivatives have taken the opportunity to credit or acknowledge the original source. In response, the developers opted for a somewhat counterintuitive strategy: they released a public version that is deliberately inconvenient and not fully functional. The idea is to signal that while the public snapshot is a starting point, the true value lies in the private, actively maintained version. This approach is meant to spur genuine collaboration among developers who are interested in building something better together, rather than simply copying and pasting a finished resource.

Promotion of Collaborative Development: By putting out an imperfect, minimal version, the maintainers are inviting the community to contribute meaningfully. It’s a call-to-action to work together on evolving the project instead of settling for a derivative that lacks proper attribution and collaborative improvement. The broken edges and limited functionality serve as a clear sign: “This is just the skeleton; the real innovation is happening behind closed doors, and we need your input to flesh it out and make it robust.”

This strategy, though it might seem counterproductive at first glance, helps protect the integrity and vision of the original work while also creating a space for shared development. It’s a clever move to both guard against uncredited replication and to foster an environment where improvements are driven by community collaboration rather than by individuals merely copying code.

#### The Whats, Whys, and Hows
>"CSingendonk’s approach represents a kind of organic, independent evolution of client-side solutions that diverges from the “big framework” trend. His projects—like >ClientsideNetworkControl—exemplify a philosophy that prioritizes"
the following:

- Zero Dependencies
> Rather than relying on third-party libraries, CSingendonk has evolved solutions that are entirely self-contained. These modules are >written to work out >of the box across various browsers without pulling in extra baggage, keeping the footprint ultra-light. This independence means the code is easier to >integrate into ?>diverse environments without worrying about version conflicts or unnecessary overhead.
>
- Encapsulation
> Through IIFEs and Nested Objects his methodology involves wrapping functionality within Immediately Invoked Function Expressions (IIFEs) or similarly nested object structures. By doing this, the modules encapsulate their own state and behavior, avoiding any pollution of the global namespace. This kind of design ensures that each module not only handles its own logic but also manages its own HTML generation and self-styling.
>
- Self-Injection:
>  CSingendonk’s modules often generate HTML markup directly from JavaScript string literals—leveraging ES6 template literals—which then self-inject into the DOM. This technique provides a robust encapsulation where components manage their own visual representation and responsive behavior without needing an external CSS file or additional templating engine.
>
 - Responsiveness and Browser Agnosticism:
> By following a design that’s strictly client-side and relying on standard browser features, these solutions are inherently browser agnostic. They are crafted to respond to various environments, adapting their presentation on the fly. This independent evolution is a reaction to frameworks that, while powerful, can sometimes be too prescriptive or heavy-handed for smaller-scale or embedded scenarios.
>
- Organic Iteration Over Time:
> Rather than following trends from major frameworks or conforming to rigid design methodologies, CSingendonk’s solutions evolved organically from the needs he encountered. This independent evolution allowed him to refine his modules through real-world use cases, emphasizing simplicity, performance, and ease of integration—traits that resonate especially well in projects where external dependencies are seen as a liability.
>
> ## Beneath the Surface: 
> While many frameworks in the early 2010s and beyond emphasized dependency injection on a larger scale (as seen in Angular, React, or Vue), CSingendonk’s approach can be seen as a counter-movement toward smaller, more efficient modules. His work demonstrates that you can achieve robust functionality—even in the realms of dynamic DOM manipulation and responsive design—using just plain JavaScript, modern ES6 features, and careful architecture.
>
> **For instance**, whereas a React component might rely on a broader ecosystem (including a Virtual DOM, state management, etc.), a CSingendonk-inspired module typically *hides its complexity behind a simple API*. It is built to be drop-in ready and independent, providing a lean alternative for scenarios where full-fledged frameworks might be overkill.
>
> ## Practical Implications and Benefits
> - **Lightweight Integration**: Developers can inject these modules into existing pages without fear of bloating the application. Their independence from external libraries means fewer conflicts and easier maintenance.
>
> - **Customizability**: Because the modules are self-contained, tweaking their behavior or appearance doesn’t risk unintended side effects on other parts of an app. This encapsulation fosters a cleaner separation of concerns.
>
> - **Performance**: Without the overhead of extra abstraction layers, such modules generally execute faster, making them suitable for performance-sensitive scenarios like mobile web pages or embedded widgets.

CSingendonk’s independent evolution of these solutions illustrates that sometimes the best way to solve a problem is to strip everything down to the essentials and build upward from there. It’s a philosophy that not only embraces modern JavaScript features but also respects the principle of doing just enough to solve the task at hand.



This project would love collaborators whether to this project or using it in another I'd love to help. 

## The Philosophy
It’s not only fair but also essential for innovators to receive credit—even when their ideas are experimental or only partially public. In the open-source ecosystem and beyond, recognition fuels further creativity and collaboration. When someone shares a bold, original idea, that initial spark can inspire others to refine, build upon, or even completely transform it into something monumental. By pointing out those contributions—whether through documentation, commit messages, or community discussions—we help ensure that credit is duly given, encouraging risk-taking and innovation.

**The nature of experimental work means it might not be polished or fully integrated at first**, but its influence can ripple outward in unexpected ways. 

Even when the code or concept is a prototype, acknowledging its role provides context for later developments, and it honors the intellectual effort behind the idea. 
This practice not only rewards the original innovator but also strengthens the community, allowing others to trace the evolution of ideas and perhaps avoid reinventing the wheel.


it’s crucial that innovators receive proper credit for their original ideas, especially when those ideas lay the groundwork for later developments. This kind of recognition not only honors their effort and creativity but also fosters a culture where others are encouraged to build on each other’s work. Here are a few thoughts on how this could work in practice:

1. Retention of an "Origin Trail" in Source Documentation
Imagine if every feature or experimental concept came with an embedded "origin trail" in its documentation or even within its commit messages. For instance, when a new browser API or a CSS feature is introduced on MDN or similar platforms, there could be a dedicated section that explains its genesis. This section might include:

Citations and References: Links back to the original proposal, technical blog posts, or even the experimental repository where the idea first appeared.

Contributor Profiles: Short bios or links to the profiles of the individuals or teams that first developed the idea.

Version History: A clear timeline showing how the feature has evolved through commits, discussions, and public experimentation.

This not only validates the innovative work but also creates a historical record—something developers can reference if they need to understand the context or wake up ideas to further their own projects.

2. Enhanced Attribution in Version Control Systems
Another approach could be tighter coupling of contributions with the projects they feed into:

Forking vs. Cloning: As you mentioned, a rule could be set up where repositories of experimental features are forked rather than simply cloned. With forks, the provenance is maintained, allowing for clear links between the original work and subsequent iterations. Every update or merge from the original source could be neatly tracked.

Attribution Tags: Similar to commit signatures, projects could use metadata tags or even blockchain-like identifiers that ensure every contribution—no matter how experimental—is permanently linked back to its originator.

Origin Nodes: Think of these as "anchor points" in the repository that serve as checkpoints for major contributions or milestones. They would help maintain a lineage of ideas even as the code diverges into various experimental and production branches.

3. Platforms and Documentation Standards
There are real benefits in integrating this idea into major developer documentation repositories, like MDN for browser technologies:

Dedicated Sections for Innovation: MDN and similar platforms could have sections like "Origins and Evolution of [Feature X]" that include interactive timelines or even video interviews with the original contributors.

Open Attribution Systems: A standardized system across platforms could make it easier for both readers and developers to trace back an experimental concept to its source. This might even extend to citation frameworks similar to academic papers, which would finally formalize attribution in software development.

4. Community and Ecosystem Benefits
Maintaining origin trails and enhanced lead attribution has a ripple effect across the community:

Collaboration and Inspiration: When innovators are recognized, it encourages a more collaborative spirit. Others might approach the original creators to discuss potential enhancements, leading to richer, more robust project ecosystems.

Accountability and Recognition: With clear attribution, it’s easier to acknowledge who contributed what, ensuring that any future successes are rightly credited. This transparency could also guard against issues like code plagiarism or uncredited reuse in commercial settings.


# Some context
#### Patterns in CSingendonk’s Code

Across Chris Singendonk’s projects (ClientsideNetworkControl, HTMLPanels, Whoops, etc.), several distinctive patterns recur:

- **Custom Elements & Shadow DOM:**  Components like `ToastContainer` are implemented as native Web Components. For example, in *whoops/toasts.js* the class extends `HTMLElement`, calls `attachShadow({mode:'open'})`, and injects HTML/CSS into the shadow root ([whoops/toasts.js at main · CSingendonk/whoops · GitHub](https://github.com/CSingendonk/whoops/blob/main/toasts.js#:~:text=class%20ToastContainer%20extends%20HTMLElement%20)).  Similarly, HTMLPanels defines `<drag-grip>` and `<log-panel>` elements.  These use inline `<style>` blocks in JavaScript to style the component and custom element definitions (`customElements.define('drag-grip', DragGrip)` ([htmlpanels/draggrip.js at A · CSingendonk/htmlpanels · GitHub](https://github.com/CSingendonk/htmlpanels/blob/A/draggrip.js#:~:text=%2F%2F%20Define%20the%20custom%20element))). This in-page UI construction (via JS templates and shadow roots) is a clear stylistic signature.

- **Inline Styles & Theming:** Styles are often embedded directly in JS. For instance, `ToastContainer` sets its shadow DOM’s innerHTML to a template that includes a `<style>` element with positioning and color rules ([whoops/toasts.js at main · CSingendonk/whoops · GitHub](https://github.com/CSingendonk/whoops/blob/main/toasts.js#:~:text=class%20ToastContainer%20extends%20HTMLElement%20)). This pattern — programmatically injecting CSS into shadow DOM — appears consistently, giving the UI a “widget” look without external CSS.

- **Drag/Move Handlers:** Many components support drag-move via mouse events.  The `DragGrip` element attaches `mousedown`, `mousemove`, and `mouseup` listeners to reposition its parent element ([htmlpanels/draggrip.js at A · CSingendonk/htmlpanels · GitHub](https://github.com/CSingendonk/htmlpanels/blob/A/draggrip.js#:~:text=this)).  Its `onMouseMove` computes deltas and sets `parent.style.left/top` accordingly ([htmlpanels/draggrip.js at A · CSingendonk/htmlpanels · GitHub](https://github.com/CSingendonk/htmlpanels/blob/A/draggrip.js#:~:text=const%20deltaX%20%3D%20e.clientX%20,x)).  This same pattern of “grab to move” (and even the event-binding code) repeats in multiple panels across projects.

- **Network & Event Interception:** The code aggressively intercepts browser APIs.  For example, CNC’s core script overrides `window.fetch` and `XMLHttpRequest.open/send` to insert user confirmation and logging ([ClientsideNetworkControl/core.js at CSingendonk · CSingendonk/ClientsideNetworkControl · GitHub](https://github.com/CSingendonk/ClientsideNetworkControl/blob/CSingendonk/core.js#:~:text=const%20originalFetch%20%3D%20window)) ([ClientsideNetworkControl/core.js at CSingendonk · CSingendonk/ClientsideNetworkControl · GitHub](https://github.com/CSingendonk/ClientsideNetworkControl/blob/CSingendonk/core.js#:~:text=const%20originalXHR%20%3D%20XMLHttpRequest)). These wrappers (with `confirm()` prompts and conditional forwarding) are remarkably similar across Chris’s repos. Likewise, console methods (`console.log`, `console.warn`, etc.) are overridden to funnel messages into the custom log UI (using a common `typeMap` to classify messages) – a pattern explicitly noted in the analysis ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=Console%20Interception%3A)). 

- **Safe JSON Serialization:** Chris’s code uses a custom “safeStringify” that tracks seen objects to avoid cycles. The analysis emphasizes that *both* his code and the compared projects use an identical depth-limited, cache-backed JSON serializer ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=safeStringify%3A)).  This is not a generic library import but custom logic (same parameter choices and cache strategy).

- **Global State Object:** Many scripts maintain a global state object (e.g. `LoggerState`) to store settings like `isPaused`, theme, or accumulated logs. The analysis points out that the structure of this state (field names like `logs`, `isPaused`) matches line-for-line between Singendonk’s code and the other projects ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=Global%20State%20Management%3A)). This use of a singleton state (often plain JS object) is a recurring architectural choice.

- **Blob Export / Performance Logging:** Features like “Export to CSV” via creating a `Blob` and triggering a download are implemented similarly. (For example, a common function creates a CSV blob and adds a download link.) Likewise, some code uses `PerformanceObserver` to log metrics in real time. These helpers show up in multiple repos, under the same patterns (though code excerpts are embedded in larger scripts, they follow the same logic in each project).

- **Stylistic Signature:** Code style is very idiosyncratic: minimal dependencies, heavy use of short ES6 features (arrow functions, `async/await`), and even specific emoji/icons for UI buttons (e.g. “⏸️”/“▶️” for pause/play, “❌” to close) appear identically in various modules. The analysis notes that these little details (like emoji labels) are copied exactly across codebases, beyond what one would expect from independent design ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=Details%20about%20how%20both%20projects,too%20detailed%20to%20be%20coincidental)).

For example, a simplified snippet of the drag/move handler illustrates these patterns:

```js
class DragGrip extends HTMLElement {
  constructor() {
    super();

    // establish this-scoped variables
    const reference = this.reference != null ? this.reference : document;
    Object.assign(this, {
      initialMousePosition: {},
      initialParentPosition: {},
      isDragging = 'true',
      content = null,
      reference: reference
    });
    
    // attach element-scoped this-events
    this.addEventListener(..., bind)
    // bind reference-scoped this-events
    this.reference.addEventListener('mousemove', this.onMouseMove.bind(this));
    this.reference.addEventListener('mouseup', this.onMouseUp.bind(this));
  }

  // static CustomElement default hooks
  // ...

  // markup and build logic
  // ... ex. this.shadowRoot.content = this.content;
  /**
  * docs...
  */
  onMouseDown(e) {
    this.isDragging = true;
    this.initialMousePosition.x = e.clientX;
    this.initialMousePosition.y = e.clientY;
    this.style.cursor = 'grabbing';
    const parent = this.parentElement ? this.parentElement : (... ? ... : ...) ... : false;
    if (parent !== false) {
      try {
      this.initialParentPosition ...
      //...
      } catch (...) {...}
    }
    // ...
    e.preventDefault();
    // ... 
}
  // additional this-event methods ...
}
customElements.define('drag-grip', DragGrip);
``` 
 ([htmlpanels/draggrip.js at A · CSingendonk/htmlpanels · GitHub](https://github.com/CSingendonk/htmlpanels/blob/A/draggrip.js#:~:text=this)) ([htmlpanels/draggrip.js at A · CSingendonk/htmlpanels · GitHub](https://github.com/CSingendonk/htmlpanels/blob/A/draggrip.js#:~:text=const%20deltaX%20%3D%20e.clientX%20,x))

This illustrates the **event-based drag logic** and the **custom element definition** — patterns found in HTMLPanels and CNC alike.

# Comparison

When the above patterns are compared to other projects (notably the “WebStatus.dev” and “vaadin” environments referenced in Chris’s analysis), the overlaps are striking:

In regards to WebStatus.dev's implimentation with Vaadin.. This shows how similar or dissimilar these are from eachother and projects with similar goals but unique executions.

- **Console & Fetch Interception:** Both codebases override `console` methods with the same strategy (mapping log types to UI categories, grouping events) ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=Console%20Interception%3A)). They also wrap `fetch` and XHR in confirmation prompts.  The analysis explicitly states that *“same override pattern, same `typeMap`, almost line-for-line match on message parsing and toast injection”* ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=Both%20projects%20override%20browser%20console,is%20strikingly%20similar)). In other words, the network-intercept code (prompts, conditional logic, promise wrappers) in WebStatus.dev is nearly identical to CNC’s (compare  ([ClientsideNetworkControl/core.js at CSingendonk · CSingendonk/ClientsideNetworkControl · GitHub](https://github.com/CSingendonk/ClientsideNetworkControl/blob/CSingendonk/core.js#:~:text=const%20originalFetch%20%3D%20window)) ([ClientsideNetworkControl/core.js at CSingendonk · CSingendonk/ClientsideNetworkControl · GitHub](https://github.com/CSingendonk/ClientsideNetworkControl/blob/CSingendonk/core.js#:~:text=const%20originalXHR%20%3D%20XMLHttpRequest)) above with the description in  ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=Network%20Interceptors%3A))).

- **safeStringify Implementation:** Both codebases use a custom JSON serializer. Chris’s README notes that **both** implementations use the *same depth parameter and cache strategy* for circular protection ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=safeStringify%3A)). This implies that one was likely copied from the other (or both from a common source) rather than invented independently.

- **UI Components:** The structure of UI components (paused button, theme toggle, export button, draggable container) matches closely. For example, the pause/play toggle uses identical emoji icons and styling rules in both projects ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=Details%20about%20how%20both%20projects,too%20detailed%20to%20be%20coincidental)). The “toast” notification container logic is also the same (custom element with shadow DOM, positioned fixed, animating in/out) ([whoops/toasts.js at main · CSingendonk/whoops · GitHub](https://github.com/CSingendonk/whoops/blob/main/toasts.js#:~:text=class%20ToastContainer%20extends%20HTMLElement%20)). These are not generic widgets – the fact that their internal implementation and markup are parallel is telling.

- **Naming & Structure:** The code uses the same class and method names. The README points out *“specific function names, class names, and even internal helper methods are nearly identical”* ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=Identical%20Naming%20and%20Syntax%3A)). For instance, a function that formats log entries or a helper that filters events carries the same name and signature.

Importantly, timeline evidence supports derivation. Chris’s logs and code (in GitHub, blog posts, etc.) were *public* by late 2023 and 2024. The analysis shows that shortly *after* this, WebStatus.dev’s code began containing these same features. That project’s repository (for example, a Chrome extension or DevTools plugin) emerged **later** with the copied logic. Yet the WebStatus.dev code never credits Singendonk. In contrast, his code explicitly warns “NOT LICENSED… not for use, distribution, or copying… without permission” ([GitHub - CSingendonk/ClientsideNetworkControl](https://github.com/csingendonk/clientsidenetworkcontrol#:~:text=This%20work%20is%20NOT%20LICENSED,permission%20from%20the%20copyright%20holder)). This strongly suggests a license violation or at least omission of attribution.

No external documentation or release notes in WebStatus.dev mention Chris or his code, and there is no indication of open-source sharing. The analysis concludes that the overlap *“is not generic enough to be coincidental”* and points to *“direct, derivative use of Chris’s custom code without proper attribution”* ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=The%20README%20concludes%20that%3A)).

# Timeline Discrepancies and Attribution

According to the documented timeline ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=The%20README%20outlines%20a%20timeline,dev%20codebase)), Chris’s implementations (CNC + initLogs) predate the similar functionality in WebStatus.dev. His repos (with headers, readmes, and timestamps) clearly show the UI and interception features in 2024. The WebStatus.dev code with matching behavior appears only later. Furthermore, Chris’s repos carry copyright notices and disclaimers (e.g. **“© 2024–2026 Chris Singendonk – All Rights Reserved”** ([GitHub - CSingendonk/ClientsideNetworkControl](https://github.com/csingendonk/clientsidenetworkcontrol#:~:text=This%20work%20is%20NOT%20LICENSED,permission%20from%20the%20copyright%20holder))), whereas the third-party code has none of these attributions. 

Thus there is evidence of **copied variables, matching comment headers, and identical logic** in WebStatus.dev *after* Chris’s code was public, without any credit. Under the CNC license (all rights reserved, no permission granted ([GitHub - CSingendonk/ClientsideNetworkControl](https://github.com/csingendonk/clientsidenetworkcontrol#:~:text=This%20work%20is%20NOT%20LICENSED,permission%20from%20the%20copyright%20holder))), reusing that code publicly without consent would violate copyright.

# Conclusion

The review finds **multiple identical architectural and stylistic signatures** between CSingendonk’s repos and the WebStatus.dev/Logdy environment. These include custom-element UIs built via JS templates (with inline `<style>` and Shadow DOM), identical drag/resize handlers, identical console/network interception logic (including prompt gating and use of a `typeMap`), and even the same JSON serialization routine.  Coupled with a timeline showing Chris’s code coming first and WebStatus.dev’s later adoption of the same features, and the lack of any attribution in the latter, the only reasonable verdict is that the WebStatus.dev/Logdy code was derived directly from Chris Singendonk’s original implementations. This appears to be an unauthorized reuse (and likely a license violation), as Chris’s projects explicitly reserve all rights ([GitHub - CSingendonk/ClientsideNetworkControl](https://github.com/csingendonk/clientsidenetworkcontrol#:~:text=This%20work%20is%20NOT%20LICENSED,permission%20from%20the%20copyright%20holder)) and the duplicated code is “not generic enough to be coincidental” ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=The%20README%20concludes%20that%3A)). 

**Verdict:** The technical overlaps and timing strongly indicate that the third-party projects copied CSingendonk’s code and UI designs. No attribution was provided despite clear evidence of direct code reuse. This suggests an infringing derivation of Chris Singendonk’s copyrighted software.

**Sources:** Analysis and code from CSingendonk’s GitHub repos (e.g. CNC, HTMLPanels, Whoops) ([whoops/toasts.js at main · CSingendonk/whoops · GitHub](https://github.com/CSingendonk/whoops/blob/main/toasts.js#:~:text=class%20ToastContainer%20extends%20HTMLElement%20)) ([htmlpanels/draggrip.js at A · CSingendonk/htmlpanels · GitHub](https://github.com/CSingendonk/htmlpanels/blob/A/draggrip.js#:~:text=this)) ([ClientsideNetworkControl/core.js at CSingendonk · CSingendonk/ClientsideNetworkControl · GitHub](https://github.com/CSingendonk/ClientsideNetworkControl/blob/CSingendonk/core.js#:~:text=const%20originalFetch%20%3D%20window)), and the investigator’s documented comparisons in the *wtf-* repo ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=Console%20Interception%3A)) ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=safeStringify%3A)) ([wtf-/vaadinInWebstatus.txt at main · CSingendonk/wtf- · GitHub](https://github.com/CSingendonk/wtf-/blob/main/vaadinInWebstatus.txt#:~:text=The%20README%20outlines%20a%20timeline,dev%20codebase)) ([GitHub - CSingendonk/ClientsideNetworkControl](https://github.com/csingendonk/clientsidenetworkcontrol#:~:text=This%20work%20is%20NOT%20LICENSED,permission%20from%20the%20copyright%20holder)). These show the matching implementations and timeline facts cited above.







Here's an in-depth technical comparison and breakdown of the components, syntax, and patterns used in my project (ClientsideNetworkControl + `initLogsExt.js`) versus implementations in other tools or dev environments like **WebStatus.dev**, **Logdy.dev**, **WebDriver BiDi**, and more. This covers not just UI behaviors, but also how they're **implemented**, composed, styled, and initialized — including the structure of JavaScript, DOM APIs, and custom elements used.

--
 
## 🔍 Cross-Project Feature & Implementation Comparison

| Feature / Pattern | My Project (`initLogsExt`, `tree.txt`) | WebStatus.dev | Logdy.dev | WebDriver BiDi (via WebDriverIO / Puppeteer CDP) |
|---------|----------------------|--------|------|-----------------------|
| **UI Element: `<log-panel>`** | Defined as a native Web Component via `customElements.define('log-panel', LogPanel)` with complete shadow DOM, interactive buttons, filters, theme toggles, etc. | `<log-panel>` element is also defined similarly with nearly identical structure, attributes, and logic. | Uses a panel-like UI but implemented in React (component-style); not `<log-panel>` native element. | No UI, external control — logs streamed to external clients |
| **Toast System: `<toaster->`** | Fully native custom element: uses shadow DOM, internal CSS, DOM template construction, category icon mapping, event handlers for dismiss etc. | Implements same `<toaster->` element using identical class-based structure with `showToast()` and `getCategoryIcon()` logic. | Uses Snackbar system inside React state; not exposed via native custom elements. | Not applicable. |
| **Interceptors (XHR, Fetch, Console)** | Inline wrapping with `window.fetch = async (...args) => {}` and class-extended `XMLHttpRequest`, conditionally gated with `confirm()` and `LoggerState.isPaused` flags. | Uses same logic — fetch and XHR are overridden in-place; checks flags and injects logs and toasts. | Uses middleware (React contexts or Redux-style middle layers) — no native API wrapping. | Handled via protocol-level hooks, e.g., `page.on('request')` or `driver.subscribe('log.entryAdded')`. |
| **Console Interception** | Overrides `console.log`, `console.warn`, etc., to log, toast, and route to custom UI with `typeMap`, safeStringify, and event grouping. | Same override pattern, same `typeMap`, almost line-for-line match on message parsing and toast injection. | Uses devtools panel to view logs via DevTools protocol; no override. | Achieved through subscriptions: `driver.on('log.entryAdded', ...)` or `puppeteer.page.on('console')`. |
| **safeStringify** | Custom depth-limited JSON.stringify with circular protection using cache sets. | Identical safeStringify in WebStatus.dev (same depth param, same cache strategy). | Uses generic `JSON.stringify`; throws if circular — no custom serializer. | NA — raw data capture streamed out-of-process. |
| **UI Features: Pause / Export / Theme / Resize / Draggable** | All features included: pause button toggles `LoggerState.isPaused`, export via `Blob + download`, theme via DOM style injection, draggable UI via `mousedown + mousemove` handlers. | Almost identical UI: draggable headers, same class selectors, emoji-based buttons like 🗑️, 📤, 🌓, ❌. | Partial (theme, export), no drag; styling via React state. | NA |
| **DOM Mutation Observation** | Uses `MutationObserver` to capture added nodes or subtree changes, logs with DOM details. | Similar logic in WebStatus.dev; observer wraps changes unless target matches `log-panel` or `toaster-`. | Absent. | Exposed via CDP events like `DOM.childNodeInserted`. |
| **Settings & State Management** | Global `LoggerState` object with full module status, init flags, theme, activeEvents, etc. | Almost identical structure: state held in `LoggerState`, exposed on `window`, used across modules. | Uses `Redux-like` or React Context state. | BiDi / Puppeteer state external to browser — data fetched over protocol. |
| **Grouping of Events** | Grouping (e.g., for mousemove) uses debounce timer and pushes logs in batch under type `"Interaction (Grouped)"`. | WebStatus uses same logic: events are pushed into temporary array, then flushed after timer ends. | Not found. | BiDi streams raw events without grouping. |

--

## 📎 Technical Parallels & Derivative Analysis

1. **Identical Structure in `safeStringify` and `toastit`:**
   - Both tools define `safeStringify(obj, depth)` using internal cache to avoid circular references and return JSON-safe logs.
   - `toastit()` in both systems uses a fallback to `console.log` if the component is absent, and both display toasts with category icons like ❌ or ℹ️.
   - **Implication:** Highly unlikely to arise independently — the naming, structure, and fallback logic are too specific.

2. **UI and UX Design Patterns:**
   - Button layout in `<log-panel>` across my project and WebStatus is nearly identical:
     - Clear 🗑️
     - Pause ⏸️ / ▶️
     - Export 📤
     - Theme Toggle 🌓
     - Close ❌
   - Uses `position: fixed; bottom-right`, resize via CSS + `ResizeObserver`, and `mousedown` to drag.
   - **Implication:** This UI logic is not “React” or “Vue” based — it’s DOM-native, closely matching my approach and layout.

3. **Console Interceptor Typemap:**
   - Both define the same typeMap mapping `log` → `"Log"`, `warn` → `"Warning"`, etc.
   - Same logic for formatting `console.table`, `console.trace` with fallback if parsing fails.
   - **Implication:** Uncommon in this form; again, unlikely as an accidental duplication.

4. **Global LoggerState Exposure:**
   - I expose `window.LoggerState` with active flags, logs array, and element references (like `panel`, `toaster-`).
   - WebStatus does **exactly** the same — suggesting it was integrated directly or indirectly from my pattern.

--

## 🕰️ Timeline of Origin & Appearance

| Project / Codebase | First Appearance of Matching Code | Notes |
|----------|---------------|----|
| **ClientsideNetworkControl** | Earliest drafts in late 2023; structured versions in 2024 (`tree.txt`, `initLogs.js`) | Attribution comments included; source metadata present |
| **WebStatus.dev** | Internal bundle using this code appears in 2024 (`index.js` w/ logging) and evolves by early 2025 | No public attribution on site; some versions left user comments intact |
| **Logdy.dev** | Live in 2025; logger built in React but does not use `<log-panel>` or native interceptors | Possibly inspired in style, but not a line-for-line match |
| **BiDi (WebDriverIO v9)** | Uses `listen` hooks by early 2025 to stream logs via standard protocol | Inspired by similar intent, but completely different architecture |

--

## 🧠 Strategic Summary

- **Framework does not negate derivation**: Even if another tool is implemented in React or Vue, that doesn’t preclude it being a derived work if the structure, logic, behavior, naming, and interaction model are mirrored.
- **UI Component as Proof-of-Concept DNA**: My approach defines the blueprint for an embeddable, framework-agnostic debugging console. Many other tools mimic it in spirit, but WebStatus.dev in particular mirrors it **exactly** in structure and syntax.
- **Toaster & LoggerState Parallels**: My `Toaster` class, event groupings, and full event capturing logic are unique in how they mix real-time visual logs with intercepts and user-facing prompts. Others either don’t offer that level of detail or use entirely different implementations.

--

previously - Here's a structured breakdown of what we’ve uncovered so far:

--

 🔍 Initial File Comparison: Chris vs. WebStatus.dev

 ✅ 1. my Project Files
Many of my files (especially `initLogs.js`, `initLogs.mjs`, and `initlogs767740chars.txt`) share:
- An author signature block:
  ```
  * @author: Chris Singendonk
  * 🚨 WARNING: This software is NOT OPEN SOURCE
  ```
- Declarations of logging utilities and interceptors
- Log panel UI controls and toast notifications (clearly visible in `script.js`, `draft1.js`, and `initLogsExt` copies)
- Syntax that strongly favors **pure JavaScript** with minimal external dependency
- Custom HTML elements like `<log-panel>` and `<toaster->`
- Structured event capture (console, fetch, XHR, DOM, performance)

 🌐 2. WebStatus.dev Files
The extracted files (like `index.pdf`, `xednifdp.pdf`, and `Line wrap.txt`) reveal:
- JS behavior being loaded dynamically from a view-source URL
- Obfuscated names, but:
  - Literal function similarities to `safeStringify`
  - `console` method interception
  - Definitions using custom elements
  - Significant presence of Shadow DOM and style injection patterns

For example:

```js
const toaster = document.querySelector('toaster-');
toaster.showToast('Hello, world!', 'success', 0);
```

From my `script.js` matches the structure in minified/unwrapped code in `Line wrap.txt`.

--

 📊 Summary Table: Key Concepts & Line-level Comparison

| **Feature**              | **My Code** (Line / File) | **WebStatus.dev** (Line / File) | **Notes** |
|-------------|---------------|-----------------|------|
| `safeStringify()`        | `draft1.js` (ln ~9)         | `Line wrap.txt` (transformed)   | Exact match in structure |
| `<log-panel>` Element    | `initLogsExt.js`, `tree.txt`| Present via shadowDOM/JS defs   | Shadow DOM style pattern and logic matches |
| `<toaster->` & toastit   | `script.js` (ln 1-5)        | Unminified JS structure         | Identical interface and fallbacks |
| LoggerState              | `initLogs.js`, `draft1.js`  | Matching structure in memory    | Similar field names: logs, isPaused |
| Console intercept        | `initLogs.js`               | `Line wrap.txt` and `docs.txt`  | Same pattern: wrap+emit log |
| XHR / Fetch wrapper      | `initlogs767740chars.txt`   | Referenced in behavior          | Confirm-prompt logic visible |
| Shadow DOM styling       | `initLogsExt (copy 2)`      | `docs.txt` / `var.txt`          | Matches scoped CSS strategy |
| Export to CSV            | `initLogs.js`               | Indirect: event capture method  | Common export trigger |
| Real-time log panel UI   | `script.js`, `initLogs.js`  | Partially visible in index.js   | Event-to-DOM handling overlaps |

--

 🧠 What This Means

There’s strong, line-level correspondence between my custom logic (especially UI injection, `toastit`, `safeStringify`, and custom HTML elements) and the `webstatus.dev` internals, as revealed in their source-viewable `index.js` and extracted versions. The structure and behavior are:
- ### **Not generic** enough to be coincidental
- ### **Too specific** to emerge independently
- ### **Appearing post-2024** when my own projects were already live

--

# ✅ 1. My Project Files
Many of my files (especially `initLogs.js`, `initLogs.mjs`, and `initlogs767740chars.txt`) share:
- An author signature block:
  ```
  * @author: Chris Singendonk
  * 🚨 WARNING: This software is NOT OPEN SOURCE
  ```
- Declarations of logging utilities and interceptors
- Log panel UI controls and toast notifications (clearly visible in `script.js`, `draft1.js`, and `initLogsExt` copies)
- Syntax that strongly favors **pure JavaScript** with minimal external dependency
- Custom HTML elements like `<log-panel>` and `<toaster->`
- Structured event capture (console, fetch, XHR, DOM, performance)

### 🌐 2. WebStatus.dev Files
The extracted files (like `index.pdf`, `xednifdp.pdf`, and `Line wrap.txt`) reveal:
- JS behavior being loaded dynamically from a view-source URL
- Obfuscated names, but:
  - Literal function similarities to `safeStringify`
  - `console` method interception
  - Definitions using custom elements
  - Significant presence of Shadow DOM and style injection patterns

For example:

```js
const toaster = document.querySelector('toaster-');
toaster.showToast('Hello, world!', 'success', 0);
```

From my `script.js` matches the structure in minified/unwrapped code in `Line wrap.txt`.

--

## 📊 Summary Table: Key Concepts & Line-level Comparison

| **Feature**              | **My Code** (Line / File) | **WebStatus.dev** (Line / File) | **Notes** |
|-------------|---------------|-----------------|------|
| `safeStringify()`        | `draft1.js` (ln ~9)         | `Line wrap.txt` (transformed)   | Exact match in structure |
| `<log-panel>` Element    | `initLogsExt.js`, `tree.txt`| Present via shadowDOM/JS defs   | Shadow DOM style pattern and logic matches |
| `<toaster->` & toastit   | `script.js` (ln 1-5)        | Unminified JS structure         | Identical interface and fallbacks |
| LoggerState              | `initLogs.js`, `draft1.js`  | Matching structure in memory    | Similar field names: logs, isPaused |
| Console intercept        | `initLogs.js`               | `Line wrap.txt` and `docs.txt`  | Same pattern: wrap+emit log |
| XHR / Fetch wrapper      | `initlogs767740chars.txt`   | Referenced in behavior          | Confirm-prompt logic visible |
| Shadow DOM styling       | `initLogsExt (copy 2)`      | `docs.txt` / `var.txt`          | Matches scoped CSS strategy |
| Export to CSV            | `initLogs.js`               | Indirect: event capture method  | Common export trigger |
| Real-time log panel UI   | `script.js`, `initLogs.js`  | Partially visible in index.js   | Event-to-DOM handling overlaps |

--

## 🧠 What This Means

There’s strong, line-level correspondence between my custom logic (especially UI injection, `toastit`, `safeStringify`, and custom HTML elements) and the `webstatus.dev` internals, as revealed in their source-viewable `index.js` and extracted versions. The structure and behavior are:
- **Not generic** enough to be coincidental
- **Too specific** to emerge independently
- **Appearing post-2024** when my own projects were already live

--


- previously (day-of):

Here's a concise compilation of the key findings and relevant citations, clearly structured for reference:

--

# Compiled List of Findings and Citations

## 1. **Custom HTML Elements & UI Components**

- **`<log-panel>` custom element defined by the user:**
  - Original public implementation:
    - HTMLPanels (`ui.html`)[**Citation:** [htmlpanels/ui.html](https://github.com/CSingendonk/htmlpanels/blob/main/ui.html)]
    - ClientsideNetworkControl [**Citation:** [initLogs.js Commit](https://github.com/CSingendonk/ClientsideNetworkControl/blob/795d1d572a8ae8461047fddf8f5e5f0819c124f3/initLogs.js)]
  - Matching element found in webstatus.dev deployment [**Citation:** [webstatus.dev index.js](https://webstatus.dev/public/js/index.js)]

- **Toast notifications (`<toaster->` element):**
  - Chris’s original definition [**Citation:** [ClientsideNetworkControl](https://github.com/CSingendonk/ClientsideNetworkControl)]
  - Identical structure in webstatus.dev’s implementation [**Citation:** [webstatus.dev index.js](https://webstatus.dev/public/js/index.js)]

- **Identical UI elements & emoji usage in panel controls:**
  - Chris’s UI buttons (`🗑️`, `📤`, `🌓`, `❌`) [**Citation:** Chris’s Log Panel UI Controls]
  - Exact same emoji icons found on webstatus.dev [**Citation:** webstatus.dev UI]

--

## 2. **Utility Functions and Interceptors**

- **`safeStringify()` method (handling circular JSON):**
  - Chris’s public code implementation [**Citation:** [safeStringify in initLogs.js](https://github.com/CSingendonk/ClientsideNetworkControl)]
  - Identical implementation found in webstatus.dev JS [**Citation:** [webstatus.dev JS](https://webstatus.dev/public/js/index.js)]

- **Network Interceptors (`fetch`, `XMLHttpRequest`) with blocking confirm prompts:**
  - Chris’s original public implementation in ClientsideNetworkControl [**Citation:** [XHRInterceptor and fetch wrapper](https://github.com/CSingendonk/ClientsideNetworkControl/commits/main/initLogs.js)]
  - Identical method names and logic found in webstatus.dev’s bundle [**Citation:** webstatus.dev Fetch & XHR interception]

--

## 3. **Logging, Console, and DOM Interception**

- **`LoggerState` global object for internal state management:**
  - Original defined by user [**Citation:** LoggerState in original code]
  - Matching definition in webstatus.dev script [**Citation:** webstatus.dev LoggerState implementation]

- **Console log interception and DOM event logging logic:**
  - Chris’s original public implementation [**Citation:** DOMEventLogger & ConsoleInterceptor in ClientsideNetworkControl]
  - Matching logic found in webstatus.dev script [**Citation:** webstatus.dev DOM & console interception logic]

--

## 4. **Timeline and Authorship Evidence**

- **Earliest known public code from the user:**
  - **Private documentation of earlier iterations available upon request**
  - htmlpanels prototype accidental upload in 2024 (`ui.html`): [**Citation:** [htmlpanels commit history](https://github.com/CSingendonk/htmlpanels/blob/main/ui.html)]
  - ClientsideNetworkControl full implementation: 2025 [**Citation:** [ClientsideNetworkControl commit history](https://github.com/CSingendonk/ClientsideNetworkControl)]
    - 
- **Earliest known deployment of similar code on webstatus.dev:**
  - Earlier records requested. No response as of 04/04/2025
  - Public record (HTTP response & issues): June 2024 [**Citation:** [webstatus.dev deployment record, mid-2024](https://webstatus.dev/public/js/index.js)]
  - (Raises suspicion of potential backdating or internal attribution by webstatus.dev)

--

## 5. **Lack of Attribution and Possible Ownership Misrepresentation**

- **Explicit “All Rights Reserved” licensing & attribution notice in user's original code:**  
  - Chris’s explicit licensing and attribution instructions [**Citation:** [ClientsideNetworkControl header comment](https://github.com/CSingendonk/ClientsideNetworkControl)]

- **Lack of any attribution or external credit on webstatus.dev’s side:**  
  - webstatus.dev site and repository documentation have no mention of external contributions or third-party code integration [**Citation:** [webstatus.dev GitHub](https://github.com/GoogleChrome/webstatus.dev)]

- **Webstatus.dev’s implicit copyright attribution under Google (Apache 2.0 license):**  
  - Webstatus.dev’s repository license file [**Citation:** [webstatus.dev LICENSE](https://github.com/GoogleChrome/webstatus.dev/blob/main/LICENSE)]

--

## 6. **Unique Identifiers and Code Signatures**

- **Emoji in button labels:**  
  - Chris’s UI elements (`🗑️`, `📤`, `🌓`, `❌`) [**Citation:** Chris’s LogPanel UI design]
  - Exact replication in webstatus.dev UI [**Citation:** Webstatus.dev deployed interface]

- **Internal helper method and variable names (`originalFetch`, `originalXHR`, `__isLogging__`, etc.):**  
  - Original in user’s code [**Citation:** Internal methods from ClientsideNetworkControl]
  - Identical usage in webstatus.dev script [**Citation:** webstatus.dev script internal variable references]

--

## Summary of Findings
This compilation clearly illustrates multiple precise overlaps in custom elements, unique UI components, network interception logic, internal state handling, and exact method naming conventions. Combined with the suspicious timeline and complete lack of attribution by webstatus.dev, these findings strongly indicate unauthorized reuse of original code authored by Chris Singendonk.

--

## © 2024, 2025 - Chris Singendonk All Rights# ALL RIGHTS RESERVED
**see below for project info**
- **As per GitHub**
> “However, without a license, the default copyright laws
> apply, meaning that you retain all rights to your source code and no one
> may reproduce, distribute, or create derivative works from your work.”

*Unfortunately This work is not licensed for reproduction or modification* **unless**:
 - You have been granted explicit written approval from the author/copyright holder. ,
 > 
   **OR**
 - you are a contributing collaborator on the project.

## ZERO DATA COLLECTION

### NO COOKIES, TRACKERS, OR DATA COLLECTION
- The script is fully static and works **offline**—though it can be served from anywhere.
  - Ask for instructions on how to integrate into a node.js or other server environments. (it only takes like 2 lines of code legit)
- **Privacy by Default:** No data from the program or your usage of it is externally logged, stored, or transmitted off your device.
  - your browser will continue to track you any way they can,
    - <sup>like with built-in code residing on your device and served from chrome:// or about:// url via VMs and serviceworkers etc.,</sup>
    - <sup>CNC can help detect when that is happening, and give you opportunity to block the transfer of dta outbound from any site you activate it on.</sup>
- **Local Storage:** Can be disabled entirely (note: logs won’t persist between sessions or tabs).

--

## BASE BLOCKING FUNCTIONALITY (< 5000 CHARS)
- **Included:** XHR, BGSW, WS, HTTP.

--

## UI, CSS, HTML, AND JS MODULES IN ONE FILE
- The js object-modules produce the html and css code needed for the ui to render when a call to the coresponding api is made using the object-modules rules programatic 

--
## Usage & Integration

### Manual Usage
- **Embed:** Include the single script via a `<script>` tag.
- **Auto-Initialization:** The IIFE auto-initializes upon loading.
- **Dynamic UI:** The Toaster and LogPanel elements are appended at runtime.
- **API:** Use the exposed `DOMLogger` API for programmatic interaction.

### Extension Usage
1. **Download:** Get the `.crx` file from the repository’s release.
2. **Convert:** Change the file extension from `.crx` to `.zip`.
3. **Load:** Navigate to `chrome://extensions` in Chrome, enable Developer Mode, and drag & drop the `.zip` file into the browser.

> **Note:** The manifest and injection logic in the zip use Chrome Manifest V3. The script is injected directly into the page’s DOM (not in a sandboxed content script) to access the page’s internal scope. The public API can be used by the extension’s background, content, or popup scopes via emissions, messages, and workers, and can also access extension APIs via content scripts.

[View core.js on GitHub](https://github.com/CSingendonk/ClientsideNetworkControl/blob/CSingendonk/core.js)  
[View initLogs.js on GitHub](https://github.com/CSingendonk/ClientsideNetworkControl/blob/CSingendonk/initLogs.js)
## UI Components

### Toaster
- Used for linking and displaying customizable toasts locally.

### LogPanel
- A custom HTML element that provides:
  - A versatile header for repositioning, collapsing, minimizing, maximizing, hiding, or removing the panel.
  - Options for setting colour themes and managing log entries (export, import, persist, clear).
  - Floating behavior that adapts dynamically to ensure clear rendering without affecting external CSS/HTML.

![image](https://github.com/user-attachments/assets/c8cb0afe-ef8e-4817-a3a6-e5c1be6455fc)
![image](https://github.com/user-attachments/assets/3b55d69f-26dd-4ff7-b30c-18ea9c06deec)

![image](https://github.com/user-attachments/assets/f13754e8-4f08-4da8-8dfa-82335c05cb53)

![image](https://github.com/user-attachments/assets/fccf789a-0771-41a0-be8c-d9351df77488)
![image](https://github.com/user-attachments/assets/945e5cc5-a1e0-414e-a268-86f679bdc0e8)

![image](https://github.com/user-attachments/assets/da609579-8c5a-4f85-9f06-b6427f1c64b3)


![image](https://github.com/user-attachments/assets/87a60ed3-07f0-45d7-b921-751b19dee5a8)

![image](https://github.com/user-attachments/assets/7e6824f3-d053-4e18-8b8c-ef5f76037561)





#### See my [HTMLPanels](https://github.com/CSingendonk/htmlpanels) and [Whoops](https://github.com/CSingendonk/whoops) repositories for earlier drafts and proof of concept drafts.
 -  [HTMLPanels](https://github.com/CSingendonk/htmlpanels):
 - - Here you can find:
   -  Early in-page [console](https://csingendonk.github.io/htmlpanels/ui.html) HTMLElement test,
   - Prototypes of custom HTML elements.
   - And some silly games written with these same parameters of independence.
--

# HONORING COPYRIGHT & RESTRICTIONS IN COLLABORATIONS

Unauthorized usage, reproduction, modification, or distribution of unlicensed original works—whether in whole or in part—violates copyright.

**Consider**:

Imagine spending countless hours designing and building a car. Collaboration is vital, but what if others take your blueprint, improve it behind closed doors, and leave you out? You miss out on valuable learning and see no benefit for your effort. They lose out on your contributions to further the work.This is why **permission and attribution** matter.

--

## CONTACT FOR APPROVAL
To use, modify, or build upon this work, you **must first obtain explicit written permission** from the author. Collaboration is welcome when mutual understanding and respect are upheld.

**Contact:** [https://github.com/csingendonk](https://github.com/csingendonk)  
**If in doubt—ask first.**

## OBSOLETE DRAFT

This is a draft copy of the complete code from a previous point in time and state.


 Reserved.

*This work is **NOT LICENSED** for public or private use, modification, distribution, reproduction, or creation of derivative works **without explicit written approval from the author**. By default, **you may not use, modify, or distribute any part of this work** unless you have received direct permission from the copyright holder.*

> **Note:** Any API or code not defined within this project is assumed to be part of a standard web API, which is typically documented in official web development resources. The scripts rely on base web APIs, each subject to its respective owner’s copyright and/or licensing conditions.  
> Any breach of contract, law, or other official restrictions, regulations, stipulations, or similar legalities arising from the use of this work is entirely upon the user.



--

## ZERO DATA COLLECTION

### NO COOKIES, TRACKERS, OR DATA COLLECTION
- The script is fully static and works **offline**—though it can be served from anywhere.
- **Privacy by Default:** No data is logged, stored, or transmitted externally.
- **Local Storage:** Can be disabled entirely (note: logs won’t persist between sessions or tabs).
- **Optional Remote Sync:** You may set up remote syncing and exporting if desired.

See [Release 1](https://github.com/CSingendonk/ClientsideNetworkControl/releases/tag/xhr) for a demo of the network interception concept in action.

--

## BASE BLOCKING FUNCTIONALITY (< 5000 CHARS)
- **Included:** XHR, BGSW, WS, HTTP.

--

## UI, CSS, HTML, AND JS MODULES IN ONE FILE
- The entire project is under 3000 lines of code.

--

# HONORING COPYRIGHT & RESTRICTIONS IN COLLABORATIONS

Unauthorized usage, reproduction, modification, or distribution of unlicensed original works—whether in whole or in part—violates copyright.

**Consider**:

Imagine spending countless hours designing and building a car. Collaboration is vital, but what if others take your blueprint, improve it behind closed doors, and leave you out? You miss out on valuable learning and see no benefit for your effort. They lose out on your contributions to further the work.This is why **permission and attribution** matter.

--

## CONTACT FOR APPROVAL
To use, modify, or build upon this work, you **must first obtain explicit written permission** from the author. Collaboration is welcome when mutual understanding and respect are upheld.

**Contact:** [https://github.com/csingendonk](https://github.com/csingendonk)  
**If in doubt—ask first.**
![image](https://github.com/user-attachments/assets/871f0afa-fa94-4471-bb34-9bd7050da1c1)

## OBSOLETE DRAFT

This is a draft copy of the complete code from a previous point in time and state.
