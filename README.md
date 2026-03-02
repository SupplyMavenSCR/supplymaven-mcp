# SupplyMaven MCP Server

Real-time supply chain risk intelligence for AI agents via Model Context Protocol (MCP).

## Server URL

https://www.supplymaven.com/api/mcp

## What It Does

SupplyMaven provides the only real-time supply chain disruption intelligence available through MCP. The server exposes proprietary risk scores calculated from 2.45M+ records across 40+ data tables covering government energy data, commodity markets, port vessel traffic, border wait times, weather systems, and macroeconomic indicators.

## Tools

**get_supply_chain_risk** - Returns the Global Disruption Index (GDI) composite score (0-100). Synthesizes 7+ real-time data streams into a single risk score validated against COVID-19, Suez Canal blockage, and Shanghai lockdowns.

**get_pillar_scores** - Returns scores for all five GDI pillars: Transportation (30%), Energy (25%), Materials (25%), Macro (20%), plus news signal boost.

**get_manufacturing_index** - Returns the patent-pending Supply Maven Manufacturing Index (SMI) using weather-adjusted electricity demand analysis across 8 US power grids. Detects manufacturing disruptions 6-24 hours before government reports.

**get_commodity_prices** - Returns current prices for up to 31 tracked commodities including crude oil, natural gas, gold, copper, steel, aluminum, and agricultural products.

**get_port_congestion** - Returns congestion scores for 26 monitored global ports including Los Angeles, Shanghai, Rotterdam, Singapore, and other strategic trade chokepoints.

**get_disruption_alerts** - Returns active supply chain disruption alerts with severity classification (LOW, ELEVATED, MODERATE, HIGH, CRITICAL).

## Connection

Connect using SSE transport at the server URL above. No authentication required for free tier access.

## About SupplyMaven

SupplyMaven is a supply chain risk intelligence platform providing 72-hour advance warnings of supply chain disruptions. Learn more at https://www.supplymaven.com
