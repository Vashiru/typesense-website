<template>
  <div class="bg-dark text-white py-5">
    <div class="container">
      <div class="row">
        <div class="col-sm">
          <h2 class="text-center">Choose from one of our support tiers</h2>
          <div class="text-center">
            Or
            <a
              class="text-white"
              href="#"
              onclick="Beacon('navigate', '/ask/'); Beacon('open'); return false;"
              >reach out</a
            >
            to us for custom needs
          </div>
        </div>
      </div>
      <div class="row mt-5">
        <div class="col-sm">
          <div class="table-responsive">
            <table class="table table-borderless text-white">
              <thead>
                <tr class="text-center h5">
                  <th scope="col"></th>
                  <th scope="col"><span>Free</span></th>
                  <th scope="col"><span>Developer</span></th>
                  <th scope="col"><span>Business</span></th>
                  <th scope="col"><span>Enterprise</span></th>
                </tr>
              </thead>
              <tbody>
                <tr class="text-center">
                  <td class="text-right">Support Channels</td>
                  <td>
                    GitHub Issues<br />
                    Slack Community<br />
                    Weekly Office Hours
                  </td>
                  <td>
                    All channels in Free plan<br />
                    + Email
                  </td>
                  <td>
                    All channels in Developer plan<br />
                    + Phone Calls
                  </td>
                  <td>
                    All channels in Business plan<br />
                    + Video Calls<br />
                    + Private Slack
                  </td>
                </tr>
                <tr class="text-center">
                  <td class="text-right">Response SLA</td>
                  <td>Best effort</td>
                  <td>72 hours</td>
                  <td>48 hours</td>
                  <td>24 hours</td>
                </tr>
                <tr class="text-center">
                  <td class="text-right">Prioritized Feature Requests</td>
                  <td>N/A</td>
                  <td>N/A</td>
                  <td>N/A</td>
                  <td>Available</td>
                </tr>
                <tr class="text-center">
                  <td class="text-right">
                    Hands-on Implementation & Training <br />
                    <p class="small mt-3 mb-0 text-light">
                      Our team will take care of integrating Typesense into your
                      tech stack and build you a fully-functioning instant
                      search experience.
                    </p>
                  </td>
                  <td>N/A</td>
                  <td>N/A</td>
                  <td>N/A</td>
                  <td>Available at an additional cost, based on scope</td>
                </tr>
                <tr class="text-center">
                  <td class="text-right">Cost</td>
                  <td>Free</td>
                  <td>$2,000/yr</td>
                  <td>$5,000/yr</td>
                  <td>$15,000/yr</td>
                </tr>
                <tr class="text-center">
                  <td class="text-right">Covered Clusters</td>
                  <td>N/A</td>
                  <td>1</td>
                  <td>1</td>
                  <td>1</td>
                </tr>
                <tr class="text-center">
                  <td class="text-right">Additional clusters</td>
                  <td>N/A</td>
                  <td>+5% of cluster costs</td>
                  <td>+10% of cluster costs</td>
                  <td>+15% of cluster costs</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.table {
  td:not(:first-child) {
    width: 20%;
  }

  tr {
    td:first-of-type {
      color: $primary;
      font-weight: 400;
    }

    td:not(:first-of-type) {
      border-right: $primary-dark-1 1px solid;
    }

    td {
      padding-bottom: 3em;
    }
  }

  th {
    span {
      padding-bottom: 0;
      border-bottom: $primary-dark-2 1px solid;
    }
  }

  tbody:before {
    line-height: 2em;
    content: '\200C';
    display: block;
  }
}
</style>
