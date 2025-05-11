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
