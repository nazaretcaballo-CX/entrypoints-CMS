# How to create an entry point

## Before creating a new entry point

It is important that you bear in mind that an entry point has its own entity; in other words, several lists of entry points can contain that entry point. The logic behind this CMS allows the entry point to be displayed, or not, depending on the list to which it belongs and the audiences for which it is configured.

### What does this mean exactly?

A user will never see an entry point that they are not supposed to see, as long as said entry point is correctly configured.

{% hint style = "success" %} Example:

*Alice is a user of an Android device. Alice will never see an entry point that is configured to be viewed by only iOS users.* {% endhint %}

## Creating an entry point

Before creating or editing an entry point, make sure you are in the [entry point creation section](./#estoy-en-la-seccion-para-crear-o-editar-un-entrypoint).

![Sección para crear entrypoints](.gitbook/assets/seccion_entrypoints.png)

Click on the **Create entry point** button.

For each entry point, fill in the following fields:

![](.gitbook/assets/entrypoint_creacion.png)

**Default icon.** Icon associated with the entry point, which is shown when the entry points are shown in list mode. Click **Set** :outbox_tray: to add an icon.<br> :low_brightness: This is required.

**Dark icon** . *Dark mode* version of the icon associated with the entry point. Click **Set** :outbox_tray: to add an icon.<br> :low_brightness: This is optional. If you don't include it at this point, the default version will also be used in *dark mode*.

{% hint style = "warning" %} Note that this icon field is only shown if the OB requires it.

- If you do not see this field in the CMS, the entry points are not accompanied by icons in any case.
- If you do see this field in the CMS, you need to add the **Default icon** at least. {% endhint %}

**Entry point internal name**. Enter a name that describes the entry point you are creating to make it easier for you to locate it later. This name is not displayed to users.<br> :low_brightness: The name can contain both uppercase and lowercase letters, numbers, and spaces, but other characters such as underscores, accents, or other special characters are not allowed.

{% hint style = "success" %} :nerd: When you enter the internal name, think naturally about what to call it so that anyone who sees it will understand what that entry point represents.

*Example:*

**:thumbsup:* Schedule in-store appointment*<br> **:thumbsdown:* ScheduleStoreAppointmentV1* {% endhint %}

**Entry point display name**. Name of the entry point that is seen in the app. This name **is** seen by the user.

**Entry point ID**. This is built automatically based on the Entry point internal name, but you can modify it if you need to.

![](.gitbook/assets/crear_entrypoint_ID_automatico.gif)

#### **Carousel images**

Expand this section to add the images of the entry point you are creating. These are the images that are displayed when the list is configured to display in carousel mode.<br> :low_brightness: These images are not mandatory and are only shown if you are configuring Carousel view mode in the list. If you do not include images, an image with the base color of the OB will be shown.

You have the option of including two images:

- Click **Set image** :outbox_tray: to add the image to be displayed on the default carousel.
- Click **Set dark image** :outbox_tray: to add the image that will be displayed on the carrousel in night mode or *dark mode*.<br> :low_brightness: If you don't include it, the image you include for the default mode will be shown.

![](.gitbook/assets/carousel_images.png)

{% hint style = "info" %} :nerd: Remember that the required image is the one in **Set image**, on the left-hand side of the page. If you only include the Dark image, you will be asked to also include the Default Image. {% endhint %}

#### **Tracking data**

Information related to entry point tracking. The entry point tracking URL is comprised by the sum of these fields.<br> :low_brightness: All fields are optional

**Category (optional)**. Category of the entry point.

**Action (optional)**. Action associated with the entrypoint.

**Label (optional)**. Label that identifies the entry point.

![](.gitbook/assets/tracking_data.png)

### Create your first URL

Configure this section to indicate which URL the entry point leads to when the user clicks.

**Add URL**. Select one of the options:

- **Pre-configured**. Select this option to select a fixed, pre-configured URL. Click Pre-configured URL data to select a URL from the available ones. When you do, you can check (but not edit) the **URL** and provider, which is displayed in the **For** field.
- **Custom**. Select this option to manually add a URL.

![Example of Preconfigured URL and Custom URL](.gitbook/assets/AddURL_Entrypoints.png)

Click the Add URL (optional) drop-down menu again and select to add URLs based on audiences.

#### URL order

If you add more than one URL, keep in mind that the order in which they appear is important. The audiences can be exclusive i.e. each entry point goes to an audience that does not share users to whom it would apply. In that case, the order doesn't matter.

But what if the URLs have non-exclusive audiences? That is, there are users who can meet the characteristics of more than one audience at the same time. In this case, the order does matter.

The system reads from top to bottom. In other words, it will show the user the URL that it first finds when searching from the top.

Once you configure all the URLs you can sort them by *drag &amp; drop*.

{% hint style = "success" %} Example:

🥇You have configured a URL for the `sport-lovers` audience. This URL leads to a promo on some new sports channels.

🏀Configure a second URL for the `basketball-lovers` audience. In this case, the URL leads to the promo of a documentary series on the NBA.

*Alice is a user who loves sports. By the configuration of the audiences, this user is integrated into the `sport-lovers` audience and also in the `basketball-lovers` audience.*

What promo will Alice see? Well, it depends on the order in which you put the URLs:

She will see the promo of the sports channels if you put the URLs in the following order:

1. `sport-lovers`
2. `basketball-lovers`

She will see the promo about the NBA documentaries if you put the URLs in this order:

1. `basketball-lovers`
2. `sport-lovers`

{% endhint %}

You have a URL configured for the `sport-lovers` audience

You have another URL configured for the `basketball-lovers` audience

Alice is a user who loves sports. By the configuration of the audiences, this user is integrated into the `sport-lovers` audience and also in the `basketball-lovers` audience.

A URL about a super important basketball game has been configured. Another about new sports channels has also been configured.

#### How to delete a URL

Click ![](.gitbook/assets/icono_borrar.png) to delete a configured URL.

Click the **Save and publish** button to publish the changes.

Click the **Save draft** button to save your changes without publishing them. You can publish them at another time, if you need to.

## Editing an entry point

Click on the row of the entry point you want to edit. The entry point creation/editing window will open up. Make the changes you need.

{% hint style = "warning" %} Remember that there are two fields that you cannot edit: the **Internal name** field and the **ID** field {% endhint %}

When you make changes, you can:

- Save the fields but not publish them: click **Save and unpublish.**
- Save changes and publish them: Click **Save and publish**.
- Start a test: click **Save and test**.
