# Pax Dei wiki progress notes
Writing for the wiki can be a bit challenging, mostly because the current wiki doesn't come with most templates that are present in wikipedia. I could try to add those templates but there is a chance that something might go wrong and I am not willing to take the risk now. So, I will note down everything I am doing and what workarounds I am making in order to get around the challenges so that once we move to wiki.gg, we can start from scratch with a fresh setup.

I will also add files that I intend to backup.

## Pages reworked

### Pax Dei
I am copying over from https://en.wikipedia.org/wiki/Pax_Dei_(video_game) and removing all templates as we don't have any templates created. The idea is to keep these 2 articles in sync. Once we move to gg, we will create the requisite templates and then copy over from wikipedia once again, making sure to keep the link alterations done in the mediawiki site.

A major thing that gets altered is how references are handled. I have to remove the `{{cite}}` template from `<ref>` links and use `<references />` instead of the `{{reflist}}` template. These need to be brought back. Its relatively easy to bring back the references as we can copy over from Wikipedia and hence not backing it up.

I have also added the IPA pronunciation and official pronunciation to the wiki. In wikipedia, the `{{IPA-la}}` and a combination of `{{Notetag}}` and `{{NoteFoot}}` are used for added notes.

### Official Frequently Asked Questions
This page will contain all FAQs that MF decides as "official" including those posted in Discord. So, reponses to chat won't be here. FAQ that is posted in Discord but not online needs to mentioned and cited as such.

In order to check if the online FAQ has changed, create an wayback machine archive then use the "Changes" button to detect if any changes have been made since the last snapshot. Discord changes need to be manually checked though but Discord will at least create a notification if anything is added or edited.

### Community Frequently Asked_Questions
This page will contain community user created information. This can include responses to community questions. This page will be a stub until enough information is gathered.

## Pages unnecessary

- Building FAQ: Incorporated into the FAQ
- Tech FAQ: Incorporated into the FAQ
- Official FAQ: Incorporated into the FAQ
- World FAQ: Incorporated into the FAQ
- Pax Dei Name: Contains some tidbits about the name and pronunciation. Incorporated into the Pax Dei page
- Inspiration: Contains info that is already present in Extended FAQ
