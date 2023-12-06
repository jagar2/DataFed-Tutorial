

## Install Anaconda

Make sure you install anaconda

[Install Anaconda](https://docs.anaconda.com/anaconda/install/windows/)

### Get a Globus account

Follow only step 1 of instructions [here](https://docs.globus.org/how-to/get-started/) to get a Globus account.

### Get a Globus ID

Ensure that your `globus ID` is linked with your institutional ID in your globus account:

1. Log into [globus.org](https://www.globus.org/)

2. Click on `Account` on the left hand pane

3. Select the `Identities` tab in the window that opens up

You should see (at least these) two identities:

- One from your home institution (that is listed as primary with a crown)

- Globus ID (<your_username@globusid.org>)

- If you do not see the `Globus ID`, click on `Link another identity`. Select `Globus ID` and link this ID.

### Register at DataFed

1. Once you have a Globus ID, visit the [DataFed web portal](https://datafed.ornl.gov/).

2. Click on the `Log in / Register` button on the top right of the page.

3. Follow the steps to register yourself with DataFed.

4. Though you can log into the DataFed web portal with your institution’s credentials, you will need the username and password you set up during your registration for scripting.

```{note}
Your institutional credentials are not the same as your DataFed credentials. The latter is only required for using DataFed via python / CLI.
```

## Install Globus Personal Connect

[Globus Personal Connect](https://docs.globus.org/globus-connect-personal/install/windows/)

conda create -n datafed_tutorial python=3.10

## install datafed

pip install datafed

pip install protobuf==3.20.0