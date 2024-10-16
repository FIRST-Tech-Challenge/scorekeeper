This is the software used to run **traditional** in-person events.

# Welcome: Traditional Events

This GitHub repository is used to [report and track issues](https://github.com/FIRST-Tech-Challenge/scorekeeper/issues) with the _FIRST_ Tech Challenge Live Scorekeeper Software.

## Downloading the software

Starting with the 2022-2023 season, the scoring system is primarily available to download as an installer. The installers can be found at
`https://ftc-scoring.firstinspires.org/local/<season>` (and `https://ftc-scoring.firstinspires.org/local/<season>-offseason` after the season's world championship when offseason events can be hosted).

### Current Links

| Game                                    | Link                                                       |
| --------------------------------------- | ---------------------------------------------------------- |
| INTO THE DEEP (2024-2025)               | https://ftc-scoring.firstinspires.org/local/2025           |
| CENTERSTAGE (2023-2024) - Offseason     | https://ftc-scoring.firstinspires.org/local/2024-offseason |
| CENTERSTAGE (2023-2024)                 | https://ftc-scoring.firstinspires.org/local/2024           |
| POWERPLAY (2022-2023) - Offseason       | https://ftc-scoring.firstinspires.org/local/2023-offseason |
| POWERPLAY (2022-2023)                   | https://ftc-scoring.firstinspires.org/local/2023           |

The scoring system will autoupdate to the latest available version for the season on launch if connected to the internet.

### Choosing the correct installer

The website will detect the platform you are running on and offer a button to download for that platform.
![Download Local Scoring System screenshot](https://ftc-scoring.firstinspires.org/uploads/076a1482-b74a-44c4-b5c4-a6bc506170f4)

If you need to download for one system from another (e.g. the scoring computer runs Windows but you are downloading on a Mac to put on a flash drive), other systems can be found by clicking on "All platforms".
![All platforms download section screenshot](https://ftc-scoring.firstinspires.org/uploads/fbcc1663-5c1f-4bfb-8fa0-b757a746adae)

If you are downloading for macOS or for Linux and are unsure which download is correct for you, run `uname -m` in a terminal and select the corresponding download.

> [!WARNING]
> While we will address any issues reported through this repository for Linux, we are unable to provide Linux-specific event-day support and therefore encourage running the scoring system on Windows or macOS unless your event has volunteers sufficiently experienced in debugging issues on Linux.

### Advanced installer

In some cases you may not be able to run the provided installer (e.g. security policies on the scorekeeper computer). In those cases you can run the scoring system through a package that is similar to how it was provided in previous seasons.

There is a download available under the "Advanced" dropdown that works on all platforms.
![Advanced download section screenshot](https://github.com/FIRST-Tech-Challenge/scorekeeper/assets/3067361/9371f9c2-06f8-40b9-a06f-17e838c8fa44)

> [!NOTE]
> This requires a global installation of Java 17, which can be [downloaded and installed from here](https://www.azul.com/downloads/?version=java-17-lts&package=jre).

To launch, extract the zip and open the `FTCLauncher` file on macOS/Linux or the `FTCLauncher.bat` file on Windows. This version of the scoring system still has the same auto-update feature as the installer version.

## Documentation

The user documentation can be found here: [FTC Scorekeeper Manual](https://www.firstinspires.org/sites/default/files/uploads/resource_library/ftc/scorekeeper-guide.pdf).

## Reporting Issues

Click on the ["Issues" link](https://github.com/FIRST-Tech-Challenge/scorekeeper/issues) towards the upper left hand corner of the main page of this repository to navigate to the [Issue Tracking Database page](https://github.com/FIRST-Tech-Challenge/scorekeeper/issues). If you are logged in to your GitHub user account (which is available for free from GitHub) you can create and reply to issues in the database.

<p align="center"><img src="https://github.com/FIRST-Tech-Challenge/WikiSupport/blob/master/scorekeeper/issues.png" width="400"></p>
<p align="center">Click on the "Issues" link to go to the Issues page.</p>

The developers of the software requested that if you encounter a bug, you copy and archive (compress into .zip form) the "db" subdirectory and then create an issue on the Issues database and attach the .zip file to the newly created issue and save the attachment with the issue. The "db" folder is located in the "lib" subfolder.

While you are editing your issue, if you click the link called "selecting them" towards the bottom of the issue window, a dialog box will appear. You can use this dialog box to select a local file from your computer to attach to the issue that you are editing.

<p align="center"><img src="https://github.com/FIRST-Tech-Challenge/WikiSupport/blob/master/scorekeeper/selectingThem.png" width="600"></p>
<p align="center">Click on the "selecting them" link to attach a local file to your issue.</p>
