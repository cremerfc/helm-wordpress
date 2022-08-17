# helm-wordpress

Sample KOTS application that illustrates the use of Preflights based on user configuration and license type:
* Preflights only run when external database is used and/or the email settings checbox is enabled
* The preflight check for Posgres is `strict` only if the License used is set to `paid`
