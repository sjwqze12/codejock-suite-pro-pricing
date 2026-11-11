# CodeJock Suite Pro Pricing: Is $899 the Real Price, Which License Do You Need, and Is There a Discount Code? (Full Tier Comparison)

CodeJock Suite Pro lists at **$899** for a single developer license. Add a year of maintenance and it becomes **$1,099**, and renewing that maintenance later costs **$299 a year**. If you are one developer shipping an ActiveX/COM desktop application, $899 is the tier you will probably buy. The extra $200 for the maintenance bundle only pays for itself if the project will still be getting new builds 12 months from now.

On the discount question: there is no public CodeJock coupon code I could verify, in English or in Chinese. You will pay the published price on whichever page you buy from, and for readers arriving from Chinese search results that page is a reseller listing rather than codejock.com itself. The reseller sets its own checkout price, so the number that appears at checkout is the number to compare against the $899 and $1,099 reference points below.

What follows is the full price structure, which tier fits which kind of project, how the cost stacks up over three years, where the Toolkit Pro alternative fits, and what Suite Pro genuinely cannot do. Most of the buying mistakes with this product come from picking the wrong one of CodeJock's two libraries, not from overpaying.

👉 [check the current Suite Pro price at Lizhi](https://lizhi.shop/products/codejock-suite-pro?cid=7bbix2xj)

## What CodeJock Suite Pro actually costs

CodeJock sells direct from its own purchase page, and the whole price list fits in one table. Suite Pro and Toolkit Pro are priced identically, which matters later.

| License | Price | Billing | Maintenance | Best for | Buy |
| --- | --- | --- | --- | --- | --- |
| Single Developer License | $899 | One-time | Not included | One developer, one ActiveX/COM project, no need for next year's builds | [See the single-license price](https://lizhi.shop/products/codejock-suite-pro?cid=7bbix2xj) |
| Single Developer + 1-Year Maintenance | $1,099 | One-time, covers 12 months | 12 months included | Projects still in active development a year out | [View the maintenance bundle](https://lizhi.shop/products/codejock-suite-pro?cid=7bbix2xj) |
| Maintenance Renewal | $299 | Per year | Adds 12 more months | Existing license holders who want to stay current | [Compare renewal pricing](https://lizhi.shop/products/codejock-suite-pro?cid=7bbix2xj) |
| Team / Site License | Quote only | Quote | Per agreement | Studios putting several developers on the same codebase | [Ask about team licensing](https://lizhi.shop/products/codejock-suite-pro?cid=7bbix2xj) |

The license itself is a one-time purchase. Maintenance is the recurring part, and it is optional.

The gap between the first two rows is $200, which buys twelve months of updates and support. Compare that with the renewal price of $299. Buying the bundle now is cheaper than adding maintenance later, and far cheaper than the alternative most people default to, which is letting maintenance lapse and then buying a fresh $899 license when a Visual Studio or Windows theme change breaks something in the UI.

CodeJock's own page does not spell out how long the base license keeps receiving updates, or how many machines one license can activate. A third-party buying guide describes the base tier as carrying a 30-day update window and two activations. Treat those two numbers as unconfirmed until someone at CodeJock puts them in writing, because they are exactly the kind of detail that decides whether a single license covers your laptop and your desktop.

Run the three-year math before you decide. Buy the bundle and renew twice and you have spent $1,697, which is roughly $47 a month across 36 months. Buy the $899 license alone and never update, and you have spent $899 for a library that will look increasingly dated as Office and Visual Studio move on. CodeJock's current release notes lead with Office 2024 and Visual Studio 2026 theme support, which tells you what the maintenance money is actually buying.

## Which license tier fits your project

A single developer on a single ActiveX/COM product should buy the $899 license and stop reading. That is the normal case, and the maintenance bundle is not an automatic upgrade.

Buy the $1,099 bundle when the application is going to be maintained and shipped for more than a year. Desktop line-of-business software usually is. If your release cycle runs past next winter, $200 for a year of updates is a small line item against the cost of rebuilding a ribbon or a docking layout after a framework change.

Skip maintenance when the product is feature-complete, in maintenance-only mode, or heading for replacement. Paying $299 a year to keep a frozen application current makes no sense.

Anyone with two or more developers on the same codebase needs a quote. CodeJock prices per developer and quotes team or site licensing separately, so the honest answer is that the per-seat cost drops if you ask, and there is no published figure to plan against. Ask before you buy three single licenses out of habit.

The tier question people ask most often is not about tiers at all. It is about which of CodeJock's two products to buy, because Suite Pro and Toolkit Pro cost the same $899 and do not overlap:

- **Suite Pro** is the ActiveX/COM library. You need this if your host is an ActiveX container: classic Visual Basic, Delphi, older C++ Builder, or a .NET WinForms app hosting ActiveX controls.
- **Toolkit Pro** is the MFC library for Visual C++. If you write C++ with MFC, this is the one, and Suite Pro will not help you.

If your application is WPF, WinUI, MAUI, Avalonia, Qt, or Electron, neither product applies. CodeJock is a Windows desktop component vendor built around ActiveX and MFC, and no amount of theming makes it a .NET-native or cross-platform library.

👉 [see which tier is listed at checkout](https://lizhi.shop/products/codejock-suite-pro?cid=7bbix2xj)

## Is there a CodeJock discount code?

No. I found no public coupon code for Suite Pro, no seasonal sale, and no student or startup pricing published anywhere. CodeJock's own store sells at list, and the reseller listing that Chinese readers land on shows its own price at checkout. Neither is hiding a promo box you have to hunt for.

The reseller platform does have discount mechanics, and it is worth being clear about how little they matter here. Lizhi runs a member day on the 7th of each month with 1.2x points on spending, but the extra points are capped at 200, so it is not a reason to delay a purchase. It refreshes coupons on the 1st of the month by membership tier. New accounts get a first-order coupon worth ¥2 off ¥29 or ¥5 off ¥39, applied automatically at checkout, and every order gets a small cash red packet. On a purchase in the $899 range, a ¥5 coupon is a rounding error. Do not build a purchase decision around it.

One genuine warning. Codes for developer tools that circulate on forums and coupon sites are frequently not coupons at all. They are shared volume keys or leaked license credentials, and they get deactivated when the vendor notices. A license bought that way cannot be verified against your CodeJock account, which is the first thing you will need when you file a support ticket about a rendering bug.

Where the reseller channel can genuinely save money is the checkout price itself rather than a code. Compare the number on the order page against $899 and $1,099 and you will know within ten seconds whether the channel is offering anything.

## The real drawbacks

**Licensing is per developer, and team pricing is opaque.** Every seat needs its own license, and CodeJock quotes team licensing privately. That is normal for component vendors and still annoying when you are budgeting.

**$299 a year is 33% of the base price, forever.** Compared with the $899 license, the annual renewal is a third of the purchase price every year you want to stay current. Over five years a maintained single license costs more than twice the sticker price.

**The ActiveX/COM constraint is hard.** Suite Pro is not a .NET library and not cross-platform. If your roadmap includes a web client or a Mac build, you are buying into a component set that covers none of it.

**The two-product split catches people.** Same price, same website, same screenshots, incompatible runtimes. Buying Toolkit Pro for an ActiveX host, or Suite Pro for an MFC application, wastes $899 outright.

**Independent reviews are thin.** The testimonials on CodeJock's site are self-selected customer quotes from medical software and hardware companies, and they read like it. I did not find a substantial body of independent, critical reviews from working developers, which means the trial is doing more of the work than usual when you evaluate this library.

## How to buy and activate Suite Pro

1. Confirm your host is an ActiveX container. If it is MFC, stop and go look at Toolkit Pro instead.
2. Install the trial and drop the two or three controls you actually need into your existing application before you spend anything. Third-party guides put the trial at 30 days, which is enough to find out whether the ribbon and docking panes behave inside your host.
3. Decide on maintenance based on your release calendar, not on how the price feels. Twelve months of updates is $200 now or $299 later.
4. Open the product page and compare the checkout price with $899 and $1,099. If the channel price is higher than CodeJock's list, buy direct.
5. Let the platform coupon apply itself at checkout, and check the order summary for the final figure before paying. Prices on reseller listings can change, so the checkout page is the number that counts.
6. Keep the order email and license key. You will need the key for reactivation after a machine rebuild, and the order record is what proves the license is yours.

👉 [open the Suite Pro product page and check the tier](https://lizhi.shop/products/codejock-suite-pro?cid=7bbix2xj)

## FAQ

**Is there a free trial?** Yes. A 30-day trial is described in third-party buying guides, and it is the sensible way to test fit before committing $899.

**Is $899 a one-time payment?** For the license, yes. Maintenance is separate: $200 for the first year if bundled, $299 per year to renew.

**Can I install one license on two machines?** The purchase page does not state an activation limit. One third-party guide says two activations, and you should confirm that with CodeJock sales before relying on it for a laptop plus desktop setup.

**Do I need Suite Pro or Toolkit Pro?** ActiveX/COM host, Suite Pro. Visual C++ with MFC, Toolkit Pro. Both cost $899, and neither works in the other's place.

**Is it worth $899 for a small project?** List the controls you would actually use first. If the answer is a grid and a chart, the suite is a large purchase for two components, and it is worth living with the trial for a couple of weeks before deciding.

## The decision

One developer, one ActiveX/COM application, shipping for the next year: buy the $1,099 bundle. The $200 is the cheapest maintenance you will ever buy on this product, and it costs less than a single renewal.

One developer, a finished or short-lived application: buy the $899 license and skip maintenance until something actually breaks.

Two or more developers: get the team quote, and do not assume three single licenses is the cheapest configuration.

Everyone else, including anyone building in WPF, .NET, or anything cross-platform: this is not your library, and the trial will tell you so in an afternoon rather than after $899.

👉 [check today's Suite Pro price before you buy](https://lizhi.shop/products/codejock-suite-pro?cid=7bbix2xj)
