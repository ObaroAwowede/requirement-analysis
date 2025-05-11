<h1>Requirement Analysis in Software Development</h1>
<p>
 This Project focuses on crafting a comprehensive foundation for software development by documenting, analyzing, and structuring requirements
</p>

<h2>What is Requirement Analysis?</h2>
<p>
 
Requirement Analysis is the process of gathering, validating, and documenting what a software system must do and under what constraints it must work. It serves as the crucial bridge between stakeholders' requirements and the technical design and implementation phases of the Software Development Life Cycle (SDLC).
</p>
   

<h2>Why is Requirement Analysis Important?</h2>
<p>Requirement Analysis is crucisal in SDLC because it:</p>
  <li>a) Establishes a Solid Foundation - ensuring that each step (design, coding) is all in line with the user needs and stakeholder needs</li>
  <li>b) Mitigates Risk Early - we are able to identify costly, unfeasable requirements early before development starts</li>
  <li>c) Improves Quality and User Satisfaction - Aligns deliverables with stakeholder expectations, leading to higher acceptance rates at each review and in final release.</li>
  
<h1>Key Activities in Requirement Analysis.</h1>
<div>
 <li> <strong>Requirement Gathering:</strong> This initial step involves collecting a wide range of needs and constraints for the system from various sources like stakeholders, users, existing documents, and experts. Common methods include questionnaires, surveys, and interviews to create a preliminary list of what the system should do</li>
 <li> <strong>Eliciting Requirements:</strong> Going beyond simple collection, this stage actively uncovers both stated and unstated needs. Techniques like in-depth interviews, workshops, brainstorming, prototyping, use cases, and observation are used to find hidden requirements and resolve conflicting needs early on.</li>
 <li> <strong>Documenting Requirements:</strong> Once gathered and elicited, requirements are formally documented in a clear, consistent, and traceable manner, often in a Software Requirements Specification (SRS). This document acts as the main reference for developers, testers, and stakeholders, detailing what the system will do, its limitations, business rules, and assumptions.</li>
<li> <strong>Analyzing and Modeling Requirements:</strong>.
 <ol>
  <li>Analysis: This involves a close examination of the documented requirements to identify any inconsistencies, dependencies, priorities, and potential challenges. Business analysts and architects assess the clarity and feasibility of each requirement and ensure it aligns with business goals. Negotiation may occur to resolve conflicts and ensure achievable requirements.</li>
  <li>
 Modeling: Visual or formal representations of the requirements are created to improve understanding and communication. Techniques like UML diagrams (use-case, class, data-flow, activity, state machine) help stakeholders visualize the system's behavior and structure, reducing ambiguity and aiding in validation
  </li>
 </ol>

</li>
<li> <strong>Validating Requirements:</strong> This final step confirms that the documented and modeled requirements accurately reflect the stakeholders' needs and are consistent, complete, and testable. Methods like reviews, walkthroughs, inspections, defining acceptance criteria, and prototyping are used to verify accuracy. Upon successful validation, the SRS becomes the approved foundation for the design and development phases.</li>
</div>

<h2>Types of Requirements.</h2>
<ol>
 <li>
  <strong>Functional requirements</strong>
  <p>
   This defines the specific actions or behaviors that the system must perform. They describe the features, tasks, and functionalities that users should be able to accomplish, defining its operations and features
  </p>
   <ul>
    <li>User management: this includes Registration and Login, password recovery, profile management</li>
    <li>Property Listings: this includes Onboarding (submiting property details, photos, pricing), calendar management, creating, reading, updating and deleting listings</li>
    <li>Search & Discovery: Users would be able to search for property by location/date/pricing, filters & sorting is included</li>
    <li>Booking & Reservation: There should be real time availability checks for the listing, Booking Confirmation & E-mail Notifications,
Cancellation as well as Refund Policies</li>
    <li>Payment Processing: There should be Secure Checkout (credit card, PayPal, local methods), Dynamic Pricing & Fees (service fee, taxes),
Payout to Hosts (scheduled settlements, reporting)</li>
    <li>Reviews & Ratings: Guest should be able to review Hosts/Properties and there should be an Aggregate Rating Display</li>
    <li>Messaging & Notifications: Guests and hosts are able to communicate with each other, there should be notifications regarding payments, listings etc</li>
    <li>Support & Help: Users should be able to contact support when they face issues, also there should be a FAQ section</li>
   </ul>
 </li>
 <li>
  <strong>Non-Functional requirements</strong>
  <p>
   Non-functional requirements define the quality attributes of the system. They describe how the system should perform, rather than what specific actions it should take.
  </p>
   <ul>
    <li>Scalability:  The system should be able to handle a large number of concurrent users and a growing database of properties without performance degradation.</li>
    <li>Availability & Reliability: The application should be highly reliable and available to users at all times with minimal downtime.</li>
    <li>Performance: The application should have fast loading times for pages and respond quickly to user actions.</li>
    <li>Security: User data, especially payment information, should be protected with robust security measures to prevent unauthorized access and data breaches.</li>
    <li>Maintainability & Operability: The system should be designed in a way that makes it easy to update, modify, and maintain the codebase over time.</li>
    <li>Extensibility: Refers to the system's ability to be easily expanded or modified to accommodate new features, functionalities, integrations, or changes in business needs without requiring significant and disruptive alterations to the existing core architecture</li>
    <li>Usability & Accessibility: The application should be available across different platforms (e.g., web, iOS, Android). Responsive Design (mobile-first)</li>
    <li>Data Privacy & Compliance: Refers to the system's ability to handle users' personal information in a secure and confidential manner, complying with relevant regulations and respecting user preferences</li>
   </ul>
 </li>
</ol>

<h2>Use Case Diagrams.</h2>

<p> A use case diagram is a type of Unified Modeling Language (UML) diagram that visually represents the interactions between users (actors) and the system to achieve specific goals (use cases). It provides a high-level view of the system's functionality from the perspective of the users.   
The components include: </p>

<ul>
 <li>Actors: These represent external entities that interact with the system. Actors can be human users, other systems, or external hardware. They are typically drawn as stick figures. The key is that an actor is external to the system but interacts with it.</li>

 <li>Use Cases: These represent the specific goals or tasks that actors can achieve by interacting with the system. They describe a sequence of actions that provide a measurable result to the actor. Use cases are typically drawn as ovals and are named using verbs that describe the actor's goal (e.g., "Book Hotel Room," "Search for Flight").</li> 

 <li>
  Relationships: Lines connecting actors and use cases show how they interact.   
  <ol>
   <li>Association: A solid line between an actor and a use case indicates that the actor participates in that use case. It shows a communication pathway.   </li>
   <li>Include: A dashed arrow pointing from one use case to another, labeled with "&lt;&lt;include>>", indicates that the first use case includes the behavior described in the second use case. This is used to avoid redundancy by breaking down complex use cases into smaller, reusable ones. The included use case is essential for the base use case to complete. </li>  
   <li>Extend: A dashed arrow pointing from one use case to another, labeled with "&lt;&lt;extend>>", indicates that the behavior of the extended use case can be inserted into the extending use case under certain conditions. The extending use case can function independently even without the extended part. The extension point is typically defined within the base use case.  </li> 
   <li>Generalization (for Actors): A solid line with a triangular arrowhead pointing from a more specific actor to a more general actor. This indicates that the more specific actor inherits the behaviors of the more general actor and can also have its own specific interactions.   </li>
  </ol>
 </li>
 <li>System Boundary: A rectangle drawn around the use cases (and sometimes excluding the actors) represents the boundary of the system being modeled. It visually distinguishes what is inside the system from what is outside.   
</li>
</ul>

<h2>Acceptance Criteria</h2>
<p>They define the specific conditions that must be met for a requirement to be considered fully implemented and accepted by the stakeholders. Think of them as the "definition of done" for each requirement. 
 
 Essentially they provide:</p>
<li>Clear Understanding: They make requirements clear and unambiguous for everyone.</li>
<li>Precise Scope: They define the exact boundaries of each requirement, preventing scope creep.</li>
<li>Testable Conditions: They serve as the direct basis for creating test cases.</li>
<li>Requirement Validation: Defining them helps uncover flaws in the requirements early on.</li>
<li>Stakeholder Agreement: They facilitate collaboration and agreement on what's needed.</li>
<li>Objective Evaluation: They provide a measurable way to determine if a requirement is met.</li>

<h2>Acceptance Criteria for the Checkout feature in the booking management system</h2>

<ol>
 
<li>
 Successful Checkout:
 <ul>
  <li>Given a confirmed booking, when the user initiates the checkout process within the allowed timeframe, then the system should successfully record the checkout in the system.</li>
  <li>>Given a user has checked out, when the user or an administrator views the booking details, then the booking status should be clearly marked as "Checked Out"</li>
  <li>Given a successful checkout, then the system may trigger a feedback request or survey to the user (optional, depending on system features).</li>
 </ul>
 
</li>

<li>
 Checkout with Outstanding Balance:
 <ul>
  <li>Given a booking with an outstanding balance, when the user initiates checkout, then the system should prompt the user to settle the remaining balance. </li>
  <li>Given the user successfully pays the outstanding balance during checkout, then the system should record the checkout with the payment details.</li>
  <li>Given the user is unable to pay the outstanding balance during checkout (depending on system policy), then the system should either prevent checkout or mark the booking with an "Overdue Payment" status.</li>
  <li>Given the user is unable to pay the outstanding balance during checkout (depending on system policy), then the system should either prevent checkout or mark the booking with an "Overdue Payment" status.</li>
 </ul>
</li>

<li>
 Early Checkout (if allowed by policy):
 <ul>
  <li>Given a confirmed booking, when the user initiates checkout before the scheduled departure date (if the hotel policy allows), then the system should successfully record the early checkout.</li>
  <li>Given an early checkout occurs (if applicable based on policy), then the system should calculate any applicable refunds or charges based on the hotel's early departure policy.</li>
 </ul>
</li>

<li>
 Late Checkout (if allowed by policy):
 <ul>
  <li>Given a confirmed booking, when the user requests and is granted a late checkout extension by hotel staff, then the system should allow the user to checkout beyond the original departure time, up to the approved extended time.</li>
  <li>Given a late checkout occurs (if applicable based on policy), then the system should calculate any additional charges based on the hotel's late checkout policy.</li>
 </ul>
</li>

<li>
 System Updates:
 <ul>
  <li>Given a successful checkout, then the system should update the room's availability status to "available" or "ready for cleaning".</li>
  <li>Given a checkout is recorded, then the system should log the checkout event with a timestamp and the user or staff member who initiated it.</li>
 </ul>
</li>

<li>
 Error Handling:
 <ul>
  <li>Given a system error occurs during the checkout process, then the system should display a user-friendly error message and allow the user to retry or contact support.</li>
  <li>Given the user attempts to checkout before the allowed time (e.g., immediately after check-in), then the system should display a message indicating the earliest possible checkout time.</li>
 </ul>
</li>

</ol>





