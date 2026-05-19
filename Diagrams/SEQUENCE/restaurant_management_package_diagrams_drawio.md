# Restaurant Management System – Draw.io Package Diagrams

Copy each XML block into a new `.drawio` file or import it into Draw.io using:

File → Import From → Device

---

# 1. Reservation Package Diagram

```xml
<mxfile host="app.diagrams.net">
  <diagram name="Reservation Package Diagram">
    <mxGraphModel>
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        <mxCell id="pkg1" value="Reservation Management" style="swimlane" vertex="1" parent="1">
          <mxGeometry x="40" y="40" width="700" height="220" as="geometry"/>
        </mxCell>
        <mxCell id="a" value="ReservationController" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg1">
          <mxGeometry x="20" y="50" width="120" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="b" value="ReservationService" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg1">
          <mxGeometry x="190" y="50" width="120" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="c" value="AvailabilityChecker" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg1">
          <mxGeometry x="360" y="50" width="140" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="d" value="ReservationDatabase" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg1">
          <mxGeometry x="530" y="50" width="140" height="50" as="geometry"/>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
```

---

# 2. Order Flow Package Diagram

```xml
<mxfile host="app.diagrams.net">
  <diagram name="Order Flow Package Diagram">
    <mxGraphModel>
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        <mxCell id="pkg2" value="Order Management" style="swimlane" vertex="1" parent="1">
          <mxGeometry x="40" y="40" width="750" height="220" as="geometry"/>
        </mxCell>
        <mxCell id="o1" value="WaiterInterface" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg2">
          <mxGeometry x="20" y="50" width="120" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="o2" value="OrderService" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg2">
          <mxGeometry x="180" y="50" width="120" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="o3" value="KitchenService" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg2">
          <mxGeometry x="340" y="50" width="120" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="o4" value="TableManager" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg2">
          <mxGeometry x="500" y="50" width="120" height="50" as="geometry"/>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
```

---

# 3. Inventory Package Diagram

```xml
<mxfile host="app.diagrams.net">
  <diagram name="Inventory Package Diagram">
    <mxGraphModel>
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        <mxCell id="pkg3" value="Inventory Management" style="swimlane" vertex="1" parent="1">
          <mxGeometry x="40" y="40" width="750" height="220" as="geometry"/>
        </mxCell>
        <mxCell id="i1" value="InventoryService" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg3">
          <mxGeometry x="20" y="50" width="140" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="i2" value="StockChecker" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg3">
          <mxGeometry x="210" y="50" width="120" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="i3" value="AlertService" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg3">
          <mxGeometry x="380" y="50" width="120" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="i4" value="ManagerInterface" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg3">
          <mxGeometry x="550" y="50" width="140" height="50" as="geometry"/>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
```

---

# 4. Product Sales Package Diagram

```xml
<mxfile host="app.diagrams.net">
  <diagram name="Product Sales Package Diagram">
    <mxGraphModel>
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        <mxCell id="pkg4" value="Product Sales Management" style="swimlane" vertex="1" parent="1">
          <mxGeometry x="40" y="40" width="800" height="220" as="geometry"/>
        </mxCell>
        <mxCell id="p1" value="SalesInterface" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg4">
          <mxGeometry x="20" y="50" width="120" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="p2" value="ProductService" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg4">
          <mxGeometry x="190" y="50" width="120" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="p3" value="PaymentProcessor" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg4">
          <mxGeometry x="360" y="50" width="140" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="p4" value="InventoryService" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg4">
          <mxGeometry x="550" y="50" width="140" height="50" as="geometry"/>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
```

---

# 5. Reporting Package Diagram

```xml
<mxfile host="app.diagrams.net">
  <diagram name="Reporting Package Diagram">
    <mxGraphModel>
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        <mxCell id="pkg5" value="Reporting System" style="swimlane" vertex="1" parent="1">
          <mxGeometry x="40" y="40" width="850" height="240" as="geometry"/>
        </mxCell>
        <mxCell id="r1" value="ReportingService" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg5">
          <mxGeometry x="20" y="50" width="140" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="r2" value="SalesData" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg5">
          <mxGeometry x="200" y="50" width="120" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="r3" value="ReservationData" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg5">
          <mxGeometry x="360" y="50" width="140" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="r4" value="InventoryData" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg5">
          <mxGeometry x="540" y="50" width="140" height="50" as="geometry"/>
        </mxCell>
        <mxCell id="r5" value="AnalyticsEngine" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="pkg5">
          <mxGeometry x="710" y="50" width="120" height="50" as="geometry"/>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
```

