Think of a Use Case Diagram as a map that shows who uses a system and what they can do with it.

Here is the simple breakdown of how your library booking system works:

1. The People (Actors)
There are two types of people who use this system:

The Student: The everyday user who wants to find and sit in a seat.

The Librarian: The manager who keeps the system running and supervises everything.

2. What They Can Do (Use Cases)
Students can: Look for seats, book a seat, look at their list of bookings, and cancel a booking.

Librarians can: Manage the seat list (like adding new chairs or removing broken ones) and oversee everyone's bookings.

3. How the Actions Connect (Relationships)
This is where those technical terms «include» and «extend» come in. Think of them as rules for how actions connect to each other:

The "Include" Rule (Mandatory Step)
What it means: You must do action B to finish action A. It happens every single time.

In your system: Book a Seat «include» Verify Identity.

In plain English: Every single time a student tries to book a seat, the system forces them to prove who they are first. No verification, no seat.

The "Extend" Rule (Optional Step)
What it means: Action B might happen after action A, but only if you choose to or if special conditions are met. It doesn't happen every time.

In your system: This applies to things like Cancelling a Booking.

In plain English: If you are looking at your current bookings, you don't have to cancel one. But the option is there if you want to use it.
