# Artemis Ops — Release Notes

Release history for Artemis Ops.

**Period:** January 2025 → May 2026

---

## May 2026

- Windows PDF overflow and path length fixes
- Guided fill progress toggle and signature field cleanup
- Password reset capabilities
- Additional reports
- AIR form additions

## April 2026

- Clear selection when clicking a folder
- People page white screen fix
- Workflow file fetching race condition fixes
- Summarizer added to reports
- TinyURL generation for manual task create and duplication
- Shortlink service
- Multiple signature-only fields per form
- QR code trailing slash fix in shortlink service
- Long audio chunking for transcription
- Suggestions loading state to be per-response-set
- Shortlink cleanup
- Improve team editor UX with filtered dropdowns and better submit flow
- QR code close button and enlarge modal
- Guided fill v2
- Notification delete and display fixes
- Hidden paused workflows now visible with progress cleanup
- Team-based access revamp
- Pen test and dependabot security fixes

## March 2026

- Duplicate workflows, task groups, and tasks
- Folders for task groups
- Renamed end date to due date for one-time task groups
- Removed conditional query args from RTK Query hooks
- Delete entire cadence family when deleting a task group
- Summarizer and date prompt types
- Links in text prompts
- Task group folder reset after task status toggle
- Form generation Lambdas
- Response start and end times
- Missing cadence family IDs in automated workflow task groups
- Task email notifications
- Team member save and load error fixes
- Email notification display after closing task editor
- Hide empty email notifications row in task details
- Environment forms fixes
- Report labels order update
- S3 site map policy update
- Form generation bug fixes
- Add new response button on tasks
- New submission activity logging and populate fixes
- Update log when responses are deleted
- Removed censor parameter from response JSON
- Enable log file deletion from uploader
- Submitter handling via dedicated prompt type
- Questions hidden with default values
- Task group reordering selection fix
- Relaxed overly strict short-answer validation
- S3 CORS policy update
- Manager form editing
- Secondary actions can require questions
- Site profile blank-page crash fix on search
- Submitter no longer cleared on autofill
- Dependency and security updates

## February 2026

- Mid-day check-in
- Zip download fixes
- Cadence editing
- Location select prompt type for forms
- Other/discussion questions accept any language
- Company timezone and Lambda timezone fixes
- Signature legal language on forms
- Pause and unpause for workflow objects
- Cadence conversion script
- Dependency and security updates

## January 2026

- ROI event form filling adjustments
- Client forms update when events change
- Optional non-mandatory form questions
- Removed workflow files from workflow profile
- OSHA log generation
- Signature list scroll issue
- AI response checking
- Workflow summary update logic in aggregation Lambda
- Moved OpenAI calls to server-side
- For-date field on reports
- Dependency and security updates

## December 2025

- Filter workflows by asset, site, and related fields
- Event map pin fixes
- Aggregation values and status fixes
- Profile sizing and task filtering improvements
- Time formatting cleanup
- Form builder enhancements
- ROI event forms
- Task editor deletion and aggregation value fixes
- Progress bars show current completion instead of historical
- Signature fields on forms

## November 2025

- Access filter on fetch cleanup
- Report fixes and adding hours to assets
- Workflow report date fixes
- Task editor updates
- Terms and conditions scroll fix
- New associated items on task level and optional uploads and some bug fixes
- Workflow files header update
- Custom filter for form responses
- Dependency and security updates

## October 2025

- Reusable task filter drawer
- Dummy data build script
- Dashboard sizing fixes
- Single-select checkbox form fields
- JSA form templates
- Workflow reports for tasks without due dates
- TinyURL public access and form field fixes
- Workflow aggregation logic in Lambda
- File list handling improvements
- Display responses whiteout fix
- Require name and signature on task completion
- Donut chart text sizing
- Highlight and clear required form fields
- Revised secondary actions on tasks
- Form submission confirmation dialog
- Additional report bug fixes
- Dependency and security updates

## September 2025

- Data cleanup and other fixes as well as more workflow form features
- Signature-only field option fix
- Report signatures restored
- Pagination on form response display
- PDF generation moved to Lambda
- Subscription handling cleanup
- Signature dropdown fixes
- Default dates and formatting fixes
- Event description formatting
- Form builder with DynamoDB storage
- Collapsible workflow task groups
- Dependency and security updates

## August 2025

- Bulk user onboarding
- Report cleanup
- Public submission page scroll fix
- Site creation with weather forecast
- Sites weather widget sizing
- Custom PDF filling
- Form checkbox handler fix
- Auto-select first table row
- Progress filter position fix
- Workflow and response data loading performance
- OSHA table null zip code support
- Quick fix for first row select auto selecting sub tables
- Cleaned up and fixed access filtering
- Zip code leading zeros fix
- Multi-select checkbox component
- Video prompt type for forms
- Asset summary and GPT prompt cleanup
- Dashboard tab colors
- PDF filling v2
- Form autofill component
- Table vertical scroll
- Task progress update fixes
- GPT response speed improvements
- Autofill button on mobile
- Prompt type 90 fix
- Text file extension handling
- AI form suggestions
- Autofill verification for text inputs
- Team creation
- Driver forms autofill fix
- Workflow progress loading animation
- Dashboard workflow filtering fix
- Badge color updates
- Client form autofill fix
- Client form alignment fix
- Prompt cleanup
- Additional prompt cleanup
- CapEx/OpEx aggregation values

## July 2025

- Public task submission
- Filtered selector fixes
- GPT content censoring
- Progress field logic cleanup
- Converted popups to full pages
- Workflow report download
- Carousel file fetching
- Workflow filters
- Form response bug fixes
- Task checkmarks and skipping
- Team management
- Site editor
- Task list filtering
- Activity feed
- Event report download
- Workflow deletion
- Scroll task into view on selection
- People module cleanup
- Assets module cleanup
- Sites module cleanup
- Time summary report null date formatting
- Public submission layout fixes for Safari
- Event report cleanup
- Public submission bug fixes
- Canvas drawing Redux detection fix
- Report icon rendering fix
- Map sizing fix
- Adding in remaining pages and workflow features to main

## June 2025

- Asset profile popup
- Faster data loading
- Workflow editor updates
- People page redesign
- Asset editor
- New dashboard
- Tiers and classes of access
- Lender dropdown options
- Task completion steps
- Task deletion
- Gated route access control
- Client form checkbox fix
- Deletion, maps, and subscription fixes
- Sticky table headers and sorting
- Sites page
- Facilities renamed to sites with map updates
- Task form responses UI
- Person profile popup
- Asset market value updates from events
- Site profile popup
- AI-assisted workflow creation with TinyURL tasks

## May 2025

- iPad speech recognition fix
- OSHA/MSHA question language fixes for AI prompts
- Workflow report popup
- Client forms
- Overall map view
- Workflow summary and task list drawer
- Assets page
- Assets linked to events
- Dropdown multiselect fix
- Asset purchase condition field
- Site data fields and tiers of access
- Third parties on events

## April 2025

- Event summary in EventsGPT flow
- Authentication flow updates
- Demo cleanup and polish
- OSHA log editor
- MSHA log editor
- OSHA/MSHA editor fixes
- Public event forms
- Generate additional regulatory documents

## March 2025

- OSHA and MSHA GPT integration
- Event viewer updates
- Event editor address and date fixes
- Speech-to-text and validation fixes
- Event-related bug fixes and polish
- Editor updates and FilePond integration
- Event timeline view
- Login flow and UI adjustments

## February 2025

- WorkflowGPT AI-assisted workflow builder
- Speech-to-text for forms
- Event creation with review editor
- Project directory reorganization
- Mobile plus dropdown menu
- Highlight active task in workflow editor sidebar
- Events Redux integration for form filling
- Create event report editor and Google Maps integration
- Amplify backend scaffolding
- Events GPT integration
- Events page
- Amplify backend connections
- Text input translation and clarifier validation
- File uploading improvements
- Redux migration
- Authentication page redesign
- OSHA/MSHA event type differentiation

## January 2025

- Workflow creation
- Workflow creation page
