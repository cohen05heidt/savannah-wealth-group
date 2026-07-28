# Savannah Wealth Group

## Live site

### https://savannah-wealth-group.higgsfield.app

Rebranded marketing site for Savannah Wealth Group, an independent fiduciary wealth management firm with offices in Savannah and Statesboro, Georgia.

| Page | Link |
| --- | --- |
| Home | https://savannah-wealth-group.higgsfield.app/ |
| About | https://savannah-wealth-group.higgsfield.app/about |
| Services | https://savannah-wealth-group.higgsfield.app/services |
| Team | https://savannah-wealth-group.higgsfield.app/team |
| Contact | https://savannah-wealth-group.higgsfield.app/contact |

## Stack

React 19 and TanStack Start, server-rendered, deployed as a single Cloudflare Worker. Tailwind v4 for styling. The application lives in the app directory.

## Backdrop

Every page is backed by a generated drone clip that the visitor's scroll scrubs through. Touch devices receive a lighter cut on a slow loop, and reduced-motion visitors get a still frame.

## Schedule a Call

A dialog form collecting first name, last name, email, phone and how we can help, written to Cloudflare D1 through a server function.

## Content

Firm details, services, team biographies, offices and compliance disclosures all live in app/src/lib/site-data.ts

## Running it locally

From the app directory, run bun install and then bun run dev

## Compliance

Securities and advisory services offered through Commonwealth Financial Network, Member FINRA/SIPC, a Registered Investment Adviser. Required disclosures render in the site footer.
