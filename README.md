# task--1
import { Hero } from "../components/Hero";
import { FeaturedProducts } from "../components/FeaturedProducts";
import { About } from "../components/About";
import { Testimonials } from "../components/Testimonials";

export default function HomePage() {
  return (
    <>
      <Hero />
      <FeaturedProducts />
      <About />
      <Testimonials />
    </>
  );
}

