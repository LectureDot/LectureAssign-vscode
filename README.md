<img src="icon.png" align=right width=128 style="margin:0.5em">

# <span style="font-family:Trebuchet MS;font-weight:bold">Lecture<span style="color:#39d">Assign</span></span>


Visual Studio Code extension
by <span style="font-family:Trebuchet MS;font-weight:bold"><span style="color:#789">Lecture</span>Dot</span> 🎓•

Latest version (click to download): [LectureAssign v0.1.1](vsix/lecture-assign-0.1.1.vsix) - 2024-03-24  
Installation instructions [below](#installation).

----

Create, track, and review coding assignments.

The purpose of this extension is to reduce plagiarism and streamline coding assignment creation and submission.

WARNING: LectureAssign is still in beta.

If you have any issues or suggestions, please add them here: 
[Issues and Suggestions](https://github.com/LectureDot/LectureAssign-vscode/issues).


----

## Installation

While the extension is still in beta, it is not available in the VSCode marketplace.

To install this extension:

- Download the latest version of the LectureAssign extension.
- Open Visual Studio Code
- Pull down the **Help** menu, and click **Show All Commands**
- Type in "VSIX"
- Click **Extensions: Install from VSIX...**
- Locate the downloaded file **vsix** file, and click **Install**.

You may see a message (bottom-right) "Completed installing Lecture Assign extension from VSIX. Please reload Visual Studio Code to enable it." with a button **Reload Now**.  
If so:

- Click the **Reload Now** button.


----

## LectureAssign Version History

### [0.1.1](vsix/lecture-assign-0.1.1.vsix) - 2024-03-24

#### Fixed

- Fixed bug where files collected via file-pattern would be duplicates of those in the submission
- Fixed bug where in instructor-editing mode field changes got lost when attached file content was updated
- Fixed bug where in submission view changing between two file replays would retain the same content preview


### [0.1.0](vsix/lecture-assign-0.1.0.vsix) - 2024-03-17

#### Added

- Assignment creation and editing
- UUID for both assignments and submissions
- Version requirement checking
- Binary file attachments
- Instructor and student abilities to rename files and change descriptions
- Extra file bundling into submissions via file patterns
- Saving playback/chart settings when .submit file tabs change
- Saving time-based playback setting

#### Fixed

- Fixed bug where rewinding to beginning in the middle of playback caused an error


### [0.0.18](vsix/lecture-assign-0.0.18.vsix) - 2024-02-15

#### Fixed

- Fixed bug where long horizontal lines in submission content replay were causing assignment information to disappear


### [0.0.17](vsix/lecture-assign-0.0.17.vsix) - 2024-02-13

#### Added

- Time-based replay
- Saving replay speed preferences

#### Fixed

- Minor bug fixes
- Removed .track files from file explorer


### [0.0.16](vsix/lecture-assign-0.0.16.vsix) - 2024-02-02

- First stable release