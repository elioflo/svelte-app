<script>
  export let imagen;
</script>

<div>
  <div
    style="display: grid;
  grid-template-columns: auto 1fr;
  grid-template-rows: auto auto;
  column-gap: 1rem;"
  >
    <img
      src={imagen}
      alt="Pic Profile"
      style="border-radius: 100%;
    width: 2rem;
    border: .125rem solid hsl(0, 0%, 81%);
    grid-row: 1 / span 2;
    grid-column: 1 / span 1;"
    />
    <span>Daniel Clifford</span>
    <span>Verified Graduate</span>
  </div>
  <p>
    I received a job offer mid-course, and the subjects I learned were current,
    if not more so, in the company I joined. I honestly feel I got every penny’s
    worth.
  </p>
  <p
    style="
  margin: 0;
  color: hsl(0, 0%, 81%);
  font-weight: 500;
  line-height: 1.25;
  "
  >
    “ I was an EMT for many years before I joined the bootcamp. I’ve been
    looking to make a transition and have heard some people who had an amazing
    experience here. I signed up for the free intro course and found it
    incredibly fun! I enrolled shortly thereafter. The next 12 weeks was the
    best - and most grueling - time of my life. Since completing the course,
    I’ve successfully switched careers, working as a Software Engineer at a VR
    startup. ”
  </p>
</div>
