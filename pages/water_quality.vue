<template>
  <organismsHeadline> Water Quality </organismsHeadline>
  <!-- content01 -->
  <organismsBaseArticleContainerPrimary>
    <template #left>
      <organismsBaseContainerFullWidth>
        <atomsBodyTextstyle>
          Water quality rankings are provided for four parameters which were
          selected for their importance for ecosystem and human health (see
          table below):
        </atomsBodyTextstyle>
        <moleculesUnorderlistDiscStyle>
          <moleculesUnorderlistItem>
            Total phosphorus
          </moleculesUnorderlistItem>
          <moleculesUnorderlistItem>
            Phytoplankton (chlorophyll-a)
          </moleculesUnorderlistItem>
          <moleculesUnorderlistItem>
            Escherichia coli
          </moleculesUnorderlistItem>
          <moleculesUnorderlistItem>
            Nitrate-nitrogen
          </moleculesUnorderlistItem>
        </moleculesUnorderlistDiscStyle>
      </organismsBaseContainerFullWidth>

      <atomsBodyTextstyle>
        Water quality was assessed in accordance with the guidelines provided by
        the National Policy Statement for Freshwater Management 2020 (NPS-FM),
        which ranks each parameter from A (good) to D or E (poor)<sup>11</sup>.
      </atomsBodyTextstyle>

      <atomsBodyTextstyle>
        While the parameters are being measured in both lake and rivers, NPS-FM
        provides guidelines that allow us to obtain quality ratings for total
        phosphorus and chlorophyll-a for lakes only, not rivers; rankings for
        nitrate can only be obtained for rivers not lakes.
      </atomsBodyTextstyle>
    </template>
    <template #right>
      <!-- graph frame organism-->
      <organismsGraphFrame
        graph_title="Water quality measurement sites."
        flyout_id="placeholder7"
      >
        <template #flyout>
          <organismsFlyout flyout_id="placeholder7"> </organismsFlyout>
        </template>
        <template #graph>
          <img
            src="/assets/images/maps/map_water_sites.svg"
            alt="Water quality measurement sites map"
            title="Water quality measurement sites map"
          />
        </template>
      </organismsGraphFrame>
    </template>
  </organismsBaseArticleContainerPrimary>

  <atomsDivider divider_width="border-b-2" />

  <!-- content02 -->
  <organismsBaseArticleContainerQuaternary>
    <!-- graph frame organism-->
    <organismsGraphFrame
      graph_title="Water quality parameters included in this monitoring framework."
      flyout_id="placeholder8"
    >
      <template #flyout>
        <organismsFlyout flyout_id="placeholder8"> </organismsFlyout>
      </template>
      <template #graph>
        <organismsTableContainer>
          <thead>
            <tr>
              <th scope="col" class="py-3 px-6" colspan="2"></th>

              <th scope="col" class="py-3 px-6">Description</th>
            </tr>
          </thead>
          <tbody class="text-black">
            <tr class="border-b-2 border-white">
              <td class="md:py-4 md:px-6 py-1 px-2 bg-grey-500">
                Phytoplankton (chlorophyll-a)
              </td>
              <td
                class="md:py-4 md:px-6 py-1 px-2 bg-grey-300 text-center"
                rowspan="3"
              >
                Ecosystem health
              </td>
              <td class="md:py-4 md:px-6 py-1 px-2 bg-neutral-100">
                Chlorophyll-a is the green pigment in plants and algae that is
                used for photosynthesis and is a good indicator of the total
                amount of algae in a lake. Elevated chlorophyll-a concentrations
                can indicate nutrient enrichment (eutrophication), leading to
                algal blooms that disrupt the balance of aquatic life.
              </td>
            </tr>
            <tr class="border-b-2 border-white">
              <td class="md:py-4 md:px-6 py-1 px-2 bg-grey-500">
                Total phosphorus
              </td>
              <td class="md:py-4 md:px-6 py-1 px-2 bg-neutral-100">
                High levels of total phosphorus in water can come from either
                wastewater or run-off from agricultural land. Too much
                phosphorus can encourage the growth of nuisance plants such as
                algal blooms.
              </td>
            </tr>
            <tr class="border-b-2 border-black">
              <td class="md:py-4 md:px-6 py-1 px-2 bg-grey-500">
                Nitrate-nitrogen
              </td>
              <td class="md:py-4 md:px-6 py-1 px-2 bg-neutral-100">
                Nitrate-nitrogen is a very important plant nutrient but because
                it is highly water soluble, it leaches through soils and into
                groundwater very easily, particularly after heavy rainfall.
              </td>
            </tr>
            <tr class="border-b-2 border-white">
              <td class="md:py-4 md:px-6 py-1 px-2 bg-grey-500">
                Escherichia coli
              </td>
              <td class="md:py-4 md:px-6 py-1 px-2 bg-grey-300 text-center">
                Human contact
              </td>
              <td class="md:py-4 md:px-6 py-1 px-2 bg-neutral-100">
                E. coli (Escherichia coli) is an indicator of the faecal
                contamination and the presence of disease-causing organisms.
                Common sources of E.coli bacteria are human wastewater
                discharges, animal waste, bird droppings and stormwater run-off.
                E.coli is harmful to human health in high concentrations.
              </td>
            </tr>
          </tbody>
        </organismsTableContainer>
      </template>
    </organismsGraphFrame>
  </organismsBaseArticleContainerQuaternary>

  <atomsDivider divider_width="border-b-2" />

  <!-- content03 -->
  <organismsBaseArticleContainerPrimary>
    <template #left>
      <organismsBaseContainerFullWidth>
        <atomsBodyTextstyle>
          Monitoring water quality parameters provides a comprehensive
          understanding of the health of aquatic systems, their impact on human
          well-being, and the need for sustainable environmental management
          practices&#58;
        </atomsBodyTextstyle>
        <moleculesUnorderlistDiscStyle>
          <moleculesUnorderlistItem>
            Monitoring nitrate levels helps manage agricultural practices to
            minimise pollution and protect water resources&#59;
          </moleculesUnorderlistItem>
          <moleculesUnorderlistItem>
            Monitoring E.coli ensures that water sources are safe for
            recreational activities, drinking, and agricultural use&#59;
          </moleculesUnorderlistItem>
          <moleculesUnorderlistItem>
            Monitoring chlorophyll-a levels provides insight into the overall
            health of aquatic ecosystems&#59;
          </moleculesUnorderlistItem>
          <moleculesUnorderlistItem>
            Monitoring total phosphorus allows for early detection of potential
            threats to native species and habitats and it helps to identify and
            manage nutrient pollution, preventing detrimental effects, such as
            an ecological imbalance characterised by harmful algal blooms and
            oxygen depletion.
          </moleculesUnorderlistItem>
        </moleculesUnorderlistDiscStyle>
      </organismsBaseContainerFullWidth>
      <atomsBodyTextstyle>
        ORC regularly monitors the water quality around Otago, which includes
        the Upper Clutha catchment. For the most recent measurements and
        evaluations of water quality, please visit the
        <atomsReferenceTextstyle
          url="https://envdata.orc.govt.nz/AQWebPortal/Data/Map/Parameter/E-Coli%20MPN/Interval/Latest"
          >ORC Environmental Portal website</atomsReferenceTextstyle
        >.
      </atomsBodyTextstyle>
    </template>
    <template #right>
      <!-- graph frame organism-->
      <organismsGraphFrame
        graph_title="The 'current state’ of lake and river water quality in the catchment."
        flyout_id="placeholder9"
        graph_container="graph_container_large"
      >
        <template #flyout>
          <organismsFlyout flyout_id="placeholder9">
            <moleculesDatasourceItem
              link="https://envdata.orc.govt.nz/AQWebPortal/Disclaimer?returnUrl=%2FData"
              link_title="AQWebPortal"
            >
              Data were obtained from the Otago Regional Council Environmental
              Data Portal website
            </moleculesDatasourceItem>
            <moleculesDatasourceItem
              link="https://www.lawa.org.nz/"
              link_title="LAWA"
            >
              Data were obtained from the Land Air Water Aotearoa website
            </moleculesDatasourceItem>
          </organismsFlyout>
        </template>
        <template #graph>
          <div>
            <img
              src="/assets/images/graphs/current_state_of_lake.svg"
              alt="Current state of lake"
              title="Current state of lake"
            />
          </div>
        </template>
      </organismsGraphFrame>
    </template>
  </organismsBaseArticleContainerPrimary>

  <atomsDivider divider_width="border-b-2" />

  <organismsReference>
    <moleculesReferenceItem
      url="https://environment.govt.nz/publications/national-policy-statement-for-freshwater-management-2020-amended-january-2024/"
      name=" online"
      additional_info="."
    >
      [11] Ministry for the Environment, National Policy Statement for
      Freshwater Management 2020, available
    </moleculesReferenceItem>
  </organismsReference>
</template>

<script setup lang="ts">
useFlowbite();
</script>
