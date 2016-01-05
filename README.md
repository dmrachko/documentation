# Enroll 0.9-M4: New Feature Overview #

# Issues and Solutions #
The table below shows:

- the issues that Enroll users faced in previous versions
- new functionalities that solve these issues


<table>
	<tr>
		<td>
      **In previous Enroll versions...**
    </td>
		<td>
			**Now, in 0.9-M4...**
		</tr>
	<tr>
		<td>updating enrollment information (coverage dates and change reasons)
    for the opted-out applicants was not possible.</td>
		<td>enrollment administrators can update enrollment information for the opted-out applicants via the Manage Enrollment page of the Administrator Portal.
	</tr>
	<tr>
		<td>
			it was not possible to cancel an upcoming coverage if an applicant had more than one of them.
		</td>
		<td>
		enrollment administrators can cancel any of the multiple upcoming coverages, including:
		- Managed Care
		- Opt-Out
		- Temporary
		</td>
	</tr>
	<tr>
		<td>
			after a period of inactivity (specified in the Web Container configuration), the user session for both applicants and enrollment administrators had been terminated without any notice or warning and without redirecting to the Enroll landing page. The Enroll users saw error messages and had to sign in over again without understanding why.
		</td>
		<td>
			the Enroll users are automatically redirected to a custom Session Expired page after the period of inactivity, specified in the internal system configuration file. Before being redirected, a warning message is displayed that also allows users to continue working without losing the previously entered data.
		</td>
	</tr>
</table>

# Updating Enrollment Info for the Opted-Out Applicants #
*Enrollment administrators can now update the enrollment information for the opted-out applicants via the Manage Enrollment page of the Administrator Portal.*

Previously, enrollment administrators could not update enrollment information (coverage dates and change reasons) for the applicants with the Opted Out status. That was extremely inconvenient because it was impossible to update such enrollment cases to match the real-life state of things.

Now, updating the enrollment information is possible for most of the applicants, regardless of their enrollment status.
