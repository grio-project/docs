Endpoints :

* Auth
 * Firebase provides drop in UI handling multiple sign-in providers
 * https://firebase.google.com/docs/auth/web/firebaseui?authuser=0

* Get profile (post login)
 * read entry from firestore
 * https://firebase.google.com/docs/firestore/query-data/get-data?authuser=0
  * if data exists:
   * show form to fill profile
  * else if status == pending_approval:
   * show page of waiting approval
  * else:
   * load the list mentors page

* List mentors
 * paginated query from firestore
 * https://firebase.google.com/docs/firestore/query-data/query-cursors?authuser=0#paginate_a_query
 * it will return only a subset of the 

* Contact
 * write document on firestore
 * https://firebase.google.com/docs/firestore/manage-data/add-data?authuser=0#add_a_document


* all permission to read/write on fire store will be managed using security rules
 * https://cloud.google.com/firestore/docs/security/get-started
