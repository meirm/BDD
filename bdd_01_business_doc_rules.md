# Business Documentation Rules

## Document Organization
1. Feature Documentation Structure:
   - Each feature document starts with these documentation rules
   - Features are organized by business capability
   - Each feature has its own section with clear boundaries
   - Common terminology defined in a shared glossary
   - Cross-references between related features when needed

2. Feature Structure:
   - User story format (As a/I want to/So that)
   - Background section for prerequisites and context
   - Scenarios grouped by related functionality
   - Business rules section after scenarios
   - Glossary for feature-specific terms

3. Scenario Structure:
   - Given/When/Then format strictly followed
   - One primary action per scenario
   - Clear success criteria in Then statements
   - All side effects explicitly stated
   - Logging and audit requirements included

4. Table Formatting:
   - Headers use consistent naming across all scenarios
   - Related fields grouped together logically
   - Reason column included for complex cases
   - Consistent units and formats used throughout
   - Column order maintained across similar tables

## Content Guidelines
1. Completeness:
   - All related entities handled together
   - All possible outcomes documented
   - Error cases and edge conditions included
   - System responses specified
   - Logging and audit requirements detailed

2. Consistency:
   - Terminology consistent throughout all documents
   - Field ordering consistent in similar scenarios
   - Same level of detail across similar scenarios
   - Uniform format for all time specifications
   - Standard patterns for common operations

3. Clarity:
   - Each scenario has a clear, specific purpose
   - Complex behaviors broken into separate scenarios
   - Examples provided for abstract concepts
   - Calculations and formulas shown explicitly
   - Clear distinction between different types of operations

4. Dependencies:
   - Prerequisites stated in Background sections
   - Related scenarios referenced when needed
   - Impact on other features documented
   - System-wide effects noted
   - Integration points clearly specified

## Implementation Rules
1. Entity Management:
   - Related entities always handled together
   - Entity states clearly defined
   - State transitions documented
   - Access controls specified
   - Validation rules stated

2. Operations:
   - All operations fully specified
   - Success and failure conditions defined
   - Side effects documented
   - Performance expectations stated
   - Security implications noted

3. Time Handling:
   - Timezone handling specified (prefer UTC)
   - Scheduling syntax documented
   - Timing constraints defined
   - Immediate vs. scheduled changes distinguished
   - Time-sensitive operations identified

4. Audit Requirements:
   - Changes logged with before/after values
   - Actor and timestamp recorded
   - Reason for changes documented
   - Notifications specified
   - Audit trail requirements defined

## Writing Style
1. Language:
   - Use active voice
   - Be specific and precise
   - Avoid ambiguous terms
   - Define technical terms
   - Use consistent terminology

2. Formatting:
   - Use consistent indentation
   - Group related items
   - Use tables for complex data
   - Include examples for clarity
   - Follow markdown conventions

3. Maintenance:
   - Date all changes
   - Track document versions
   - Note related documents
   - Record document owners
   - Keep history of major changes

Once the BDD documentation rules and the business logic documentation is done, the next logical steps are:
Technical Design Document (TDD):
 - Convert BDD scenarios into technical requirements
 - Design the database schema for the system
 - Define API endpoints and interfaces
 - Specify the service architecture
 - Document technical implementation details